
Debian
====================
This directory contains files used to package govd/gov-qt
for Debian-based Linux systems. If you compile govd/gov-qt yourself, there are some useful files here.

## gov: URI support ##


gov-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gov-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your govqt binary to `/usr/bin`
and the `../../share/pixmaps/gov128.png` to `/usr/share/pixmaps`

gov-qt.protocol (KDE)

