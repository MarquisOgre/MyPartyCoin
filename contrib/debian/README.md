
Debian
====================
This directory contains files used to package mypartycoind/mypartycoin-qt
for Debian-based Linux systems. If you compile mypartycoind/mypartycoin-qt yourself, there are some useful files here.

## mypartycoin: URI support ##


mypartycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mypartycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mypartycoinqt binary to `/usr/bin`
and the `../../share/pixmaps/mypartycoin128.png` to `/usr/share/pixmaps`

mypartycoin-qt.protocol (KDE)

