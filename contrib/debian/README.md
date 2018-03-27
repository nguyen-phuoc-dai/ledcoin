
Debian
====================
This directory contains files used to package ledd/led-qt
for Debian-based Linux systems. If you compile ledd/led-qt yourself, there are some useful files here.

## led: URI support ##


led-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install led-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your led-qt binary to `/usr/bin`
and the `../../share/pixmaps/led128.png` to `/usr/share/pixmaps`

led-qt.protocol (KDE)

