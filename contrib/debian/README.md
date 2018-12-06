
Debian
====================
This directory contains files used to package worldcryptoforumd/worldcryptoforum-qt
for Debian-based Linux systems. If you compile worldcryptoforumd/worldcryptoforum-qt yourself, there are some useful files here.

## worldcryptoforum: URI support ##


worldcryptoforum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install worldcryptoforum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your worldcryptoforumqt binary to `/usr/bin`
and the `../../share/pixmaps/worldcryptoforum128.png` to `/usr/share/pixmaps`

worldcryptoforum-qt.protocol (KDE)

