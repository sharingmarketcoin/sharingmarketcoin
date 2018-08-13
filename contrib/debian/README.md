
Debian
====================
This directory contains files used to package smkd/smk-qt
for Debian-based Linux systems. If you compile smkd/smk-qt yourself, there are some useful files here.

## smk: URI support ##


smk-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smk-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smkqt binary to `/usr/bin`
and the `../../share/pixmaps/smk128.png` to `/usr/share/pixmaps`

smk-qt.protocol (KDE)

