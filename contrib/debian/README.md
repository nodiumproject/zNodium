
Debian
====================
This directory contains files used to package nodiumd/nodium-qt
for Debian-based Linux systems. If you compile nodiumd/nodium-qt yourself, there are some useful files here.

## nodium: URI support ##


nodium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodiumqt binary to `/usr/bin`
and the `../../share/pixmaps/nodium128.png` to `/usr/share/pixmaps`

nodium-qt.protocol (KDE)

