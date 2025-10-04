# Sddm-lain-wired-theme-2K

A sddm login screen inspired by 1998 anime ["Serial Experiments Lain"](https://myanimelist.net/anime/339/Serial_Experiments_Lain)

**Note-
This is a fork of the fork.
Original versions can be found [here](https://gitlab.com/mixedCase/sddm-lain-wired-theme) and [here](https://github.com/lll2yu/sddm-lain-wired-theme)**

This one contains changes that I made for my 2560*1440 screen.

# In action :-
You can watch the preview video [here.](https://youtu.be/M-p7cHx4OM0)

# Installation :-
**Arch Linux**

Original is available on the [AUR](https://aur.archlinux.org/packages/sddm-lain-wired-theme), you can install it with `makepkg` or using an AUR helper.
This version is not available on AUR.

Using `makepkg`:

```shell
git clone https://aur.archlinux.org/sddm-lain-wired-theme.git
cd sddm-lain-wired-theme
makepkg -Ccsi
```

**Other GNU/Linux distros**
- Make sure you have sddm installed and configured as your default login manager.
- Install the dependencies ```qt5-multimedia``` & ```qt5-quickcontrols``` using your package manager.
- Wav audio codecs are needed to play the sound, make sure you have package(s) that fulfill that installed. 
- Download the [latest release](https://github.com/Osloebishe/sddm-lain-wired-theme-2K/releases/latest)
- Decompress the `*.zip` or `*.tar.gz` file or run `git clone https://github.com/Osloebishe/sddm-lain-wired-theme-2K`
- Copy all files and directories into `/usr/share/sddm/themes/sddm-lain-wired-theme-2K/` or open a terminal and run `sudo cp -r sddm-lain-wired-theme-2K /usr/share/sddm/themes`

### Usage
- Open up your configuration file `/etc/sddm.conf` and set `sddm-lain-wired-theme-2K` as your current theme

```shell
[Theme]
# Current theme name
Current=sddm-lain-wired-theme-2K
```
- Now you are all set. Enjoy the aesthetic.
