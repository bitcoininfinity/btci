
Debian
====================
This directory contains files used to package btcad/btca-qt
for Debian-based Linux systems. If you compile btcad/btca-qt yourself, there are some useful files here.

## btca: URI support ##


btca-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install btca-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your btcaqt binary to `/usr/bin`
and the `../../share/pixmaps/btca128.png` to `/usr/share/pixmaps`

btca-qt.protocol (KDE)

