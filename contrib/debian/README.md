Debian
======

This directory contains files used to package wpsod/wpso-qt
for Debian-based Linux systems. If you compile wpsod/wpso-qt yourself, there are some useful files here.

## wpso: URI support ##

wpso-qt.desktop (Gnome / Open Desktop)

To install:

	sudo desktop-file-install wpso-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wpso-qt binary to `/usr/bin`
and the `../../share/pixmaps/wpso128.png` to `/usr/share/pixmaps`

wpso-qt.protocol (KDE)