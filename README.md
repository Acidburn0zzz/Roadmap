
Backports
---------
	x-caja-desktop fix for Petra and Maya


All Editions
------------
	pkgs: unity-greeter pkg
	pkgs: gedit-plugins pkg					
	mintlocale: missing ibus activation support	
	mintdrivers: update translations
	mintdrivers: remove the apt-cdrom repository when exiting			
	mint-mirrors: update list of mirrors			
	system: optimus cards don't work, nvidia-prime only supports LightDM (Fixed in Romeo)
	
Cinnamon
--------
	cinnamon: only 1 msgid for "Lock Screen" (action vs noun)
	cinnamon-settings: can't set hours in datetime module

MATE
----
	gparted missing from MATE edition	
	mintmenu: https://github.com/linuxmint/mintmenu/pull/89

KDE
---
	The installer doesn't install language-pack-gnome-xx resulting in GTK apps/dialogs showing in English
	also xfce, mdm: When loggin in an existing session, doesn't unlock kde screensaver, xscreensaver or gnome-screensaver (works fine with cinnamon-screensaver and mate-screensaver)
	OK Consider not using oxygen for GTK (check with mintBackup filechooser)	
	mintbackup, mintnanny, mintupload, mintdrivers, mintsources: remove KDE adjustment, add a specific KDE .desktop file
	OK missing mint-mdm-themes-kde

Xfce
----
	doesn't seem to detect DVD insertion, doesn't run VLC (works in 32bit, not 64bit)
	Can't use the trash in live mode
	There are no GTK bookmarks by default
	missing indicator-sound indicator-sound-gtk2		

 