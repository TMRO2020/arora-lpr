
Debian
====================
This directory contains files used to package lprd/lpr-qt
for Debian-based Linux systems. If you compile lprd/lpr-qt yourself, there are some useful files here.

## arora: URI support ##


lpr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lpr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lpr-qt binary to `/usr/bin`
and the `../../share/pixmaps/lpr128.png` to `/usr/share/pixmaps`

lpr-qt.protocol (KDE)

