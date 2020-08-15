
Debian
====================
This directory contains files used to package digitalaustraliandollard/digitalaustraliandollar-qt
for Debian-based Linux systems. If you compile digitalaustraliandollard/digitalaustraliandollar-qt yourself, there are some useful files here.

## digitalaustraliandollar: URI support ##


digitalaustraliandollar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install digitalaustraliandollar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your digitalaustraliandollar-qt binary to `/usr/bin`
and the `../../share/pixmaps/digitalaustraliandollar128.png` to `/usr/share/pixmaps`

digitalaustraliandollar-qt.protocol (KDE)

