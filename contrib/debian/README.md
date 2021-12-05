
Debian
====================
This directory contains files used to package funcoind/funcoin-qt
for Debian-based Linux systems. If you compile funcoind/funcoin-qt yourself, there are some useful files here.

## funcoin: URI support ##


funcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install funcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your funcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/funcoin128.png` to `/usr/share/pixmaps`

funcoin-qt.protocol (KDE)

