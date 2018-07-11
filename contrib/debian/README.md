
Debian
====================
This directory contains files used to package firelynxcoind/firelynxcoin-qt
for Debian-based Linux systems. If you compile firelynxcoind/firelynxcoin-qt yourself, there are some useful files here.

## firelynxcoin: URI support ##


firelynxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install firelynxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your firelynxcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/firelynxcoin128.png` to `/usr/share/pixmaps`

firelynxcoin-qt.protocol (KDE)

