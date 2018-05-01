
Debian
====================
This directory contains files used to package svalqod/svalqo-qt
for Debian-based Linux systems. If you compile svalqod/svalqo-qt yourself, there are some useful files here.

## svalqo: URI support ##


svalqo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install svalqo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your svalqoqt binary to `/usr/bin`
and the `../../share/pixmaps/svalqo128.png` to `/usr/share/pixmaps`

svalqo-qt.protocol (KDE)

