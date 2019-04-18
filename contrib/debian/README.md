
Debian
====================
This directory contains files used to package netrumd/netrum-qt
for Debian-based Linux systems. If you compile netrumd/netrum-qt yourself, there are some useful files here.

## netrum: URI support ##


netrum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install netrum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your netrumqt binary to `/usr/bin`
and the `../../share/pixmaps/netrum128.png` to `/usr/share/pixmaps`

netrum-qt.protocol (KDE)

