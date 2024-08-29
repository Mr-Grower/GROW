
Debian
====================
This directory contains files used to package growerd/grower-qt
for Debian-based Linux systems. If you compile growerd/grower-qt yourself, there are some useful files here.

## pivx: URI support ##


grower-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install grower-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your grower-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

grower-qt.protocol (KDE)

