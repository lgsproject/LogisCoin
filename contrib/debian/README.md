
Debian
====================
This directory contains files used to package logiscoind/logiscoin-qt
for Debian-based Linux systems. If you compile logiscoind/logiscoin-qt yourself, there are some useful files here.

## logiscoin: URI support ##


logiscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install logiscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your logiscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/logiscoin128.png` to `/usr/share/pixmaps`

logiscoin-qt.protocol (KDE)

