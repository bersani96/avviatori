# LinkIt
LinkIt is a Bash script that allows you to simplify and accelerate the creation of launchers for menu (.dekstop file).  
Launchers that are created with this script will automatically be added to your menu and, if you want it, also on your desktop.  
These launchers work on every desktop environment that follows the [Freedesktop specs](http://standards.freedesktop.org/desktop-entry-spec/latest/index.html):
KDE, Gnome, LXDE, XFCE, MATE and others!

# New version 2.2!
## Changelog
- Version 2.2:
    * Introduced a configuration file! It is `/etc/linkit.conf`.
    * Introduced a setup file.
- Version 2.1: Added the possibility to add your launchers in your desktop.

# Installation
Requirements:
- [zenity](https://help.gnome.org/users/zenity/stable/)

With these instructions you can download and extract the script :
```sh
wget https://github.com/bersani96/LinkIt/archive/master.zip
unzip master.zip
cd LinkIt-master
```
Then launch as root :
```sh
./setup.sh
```

Now you can launch the script with a simple command, or you can use the launcher in your menu.
```sh
linkit.sh
```

![Image of menu with Link It](http://sonnino1aquile.altervista.org/file/linkit-menu.png)

After you have launched the script, follow the execution and your custom launchers will be created.
The script have a GUI.
