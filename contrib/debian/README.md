
Debian
====================
This directory contains files used to package charycoind/charycoin-qt
for Debian-based Linux systems. If you compile charycoind/charycoin-qt yourself, there are some useful files here.

## charycoin: URI support ##


charycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install charycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your charycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/charycoin128.png` to `/usr/share/pixmaps`

charycoin-qt.protocol (KDE)

