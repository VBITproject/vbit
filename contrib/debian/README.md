
Debian
====================
This directory contains files used to package vbitd/vbit-qt
for Debian-based Linux systems. If you compile vbitd/vbit-qt yourself, there are some useful files here.

## vbit: URI support ##


vbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vbitqt binary to `/usr/bin`
and the `../../share/pixmaps/vbit128.png` to `/usr/share/pixmaps`

vbit-qt.protocol (KDE)

