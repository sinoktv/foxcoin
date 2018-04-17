
Debian
====================
This directory contains files used to package foxcoind/foxcoin-qt
for Debian-based Linux systems. If you compile foxcoind/foxcoin-qt yourself, there are some useful files here.

## foxcoin: URI support ##


foxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install foxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your foxcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

foxcoin-qt.protocol (KDE)

