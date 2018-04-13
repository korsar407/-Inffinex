
Debian
====================
This directory contains files used to package axscoind/axscoin-qt
for Debian-based Linux systems. If you compile axscoind/axscoin-qt yourself, there are some useful files here.

## axscoin: URI support ##


axscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install axscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your axscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/axscoin128.png` to `/usr/share/pixmaps`

axscoin-qt.protocol (KDE)

