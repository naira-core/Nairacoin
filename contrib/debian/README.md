
Debian
====================
This directory contains files used to package nairacoind/nairacoin-qt
for Debian-based Linux systems. If you compile nairacoind/nairacoin-qt yourself, there are some useful files here.

## nairacoin: URI support ##


nairacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nairacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nairacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/nairacoin128.png` to `/usr/share/pixmaps`

nairacoin-qt.protocol (KDE)

