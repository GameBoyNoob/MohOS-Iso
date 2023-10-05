MohOS livecd usb
===========================

![archiso-liveusb-gnome](https://github.com/jorisdrenth/archiso-liveusb-gnome/blob/main/archiso-liveusb-gnome.png?raw=true)

About
-----
This repo is based on the archiso-liveusb-gnome, which is used to create the monthly installation ISO's. The goal is to create a Live USB disk with a GUI so you can read the wiki while installing Arch Linux on your PC.

The following has been added:
- Gnome
- Gnome Terminal
- Firefox
- Nautilus
- Libreoffice
- nano
- xorg-drivers
- gedit
- eog
- some configs for autologin and darkmode
- [a wallpaper](airootfs/usr/local/share/backgrounds/wallpaper.png)

Usage
-----
Clone repo and create ISO with mkarchiso:
```
mkarchiso -v -o ./ archiso-liveusb-gnome
```
Add more packages to [packages.x86_64](packages.x86_64) if needed.
