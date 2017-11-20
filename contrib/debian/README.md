
Debian
====================
This directory contains files used to package lithiumd/lithium-qt
for Debian-based Linux systems. If you compile lithiumd/lithium-qt yourself, there are some useful files here.

## lithium: URI support ##


lithium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lithium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lithiumqt binary to `/usr/bin`
and the `../../share/pixmaps/lithium128.png` to `/usr/share/pixmaps`

lithium-qt.protocol (KDE)

