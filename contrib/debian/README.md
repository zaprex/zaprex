
Debian
====================
This directory contains files used to package zaprexd/zaprex-qt
for Debian-based Linux systems. If you compile zaprexd/zaprex-qt yourself, there are some useful files here.

## zaprex: URI support ##


zaprex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zaprex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zaprexqt binary to `/usr/bin`
and the `../../share/pixmaps/zaprex128.png` to `/usr/share/pixmaps`

zaprex-qt.protocol (KDE)

