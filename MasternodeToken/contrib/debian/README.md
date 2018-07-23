
Debian
====================
This directory contains files used to package MasternodeTokend/MasternodeToken-qt
for Debian-based Linux systems. If you compile MasternodeTokend/MasternodeToken-qt yourself, there are some useful files here.

## MasternodeToken: URI support ##


MasternodeToken-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install MasternodeToken-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your MasternodeTokenqt binary to `/usr/bin`
and the `../../share/pixmaps/MasternodeToken128.png` to `/usr/share/pixmaps`

MasternodeToken-qt.protocol (KDE)

