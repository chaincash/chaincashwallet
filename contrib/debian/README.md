
Debian
====================
This directory contains files used to package chaincashd/chaincash-qt
for Debian-based Linux systems. If you compile chaincashd/chaincash-qt yourself, there are some useful files here.

## chaincash: URI support ##


chaincash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chaincash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chaincashqt binary to `/usr/bin`
and the `../../share/pixmaps/chaincash128.png` to `/usr/share/pixmaps`

chaincash-qt.protocol (KDE)

