# wm
my dwl setup <br>
patches are inside the folders.

# utils:
I use this setup on void linux; it should work on either glibc or musl <br><br>
widle <br>
wlock <br>
mew (any dmenu wayland clone should work) <br>
foot<br><br>

# note:

You're going to need to edit your sudoers file so that:

sudo zzz<br>

sudo ZZZ<br>

(and optionally)<br>

sudo reboot<br>

sudo poweroff<br>


does not require a password when ran. I'm not sure if there's a better way to do this, but this method does work for the autostart patch

# Dependencoes
I'm missing a few so give me some time to update. Luckily, the compile errors should be verbose enough for you to figure it out though  <br>

```
xbps-install libinput libinput-devel wayland wayland-devel wlroots0.19 wlroots0.19-devel libxkbcommon libxkbcommon-devel wayland-protocols pkg-config xorg-server-xwayland brightnessctl tllist fcft pixman pipewire wireplumber nerd-fonts font-hack-ttf alsa-pipewire swaybg wl-clipboard
```

<br><br>

# CREDITS:
https://www.coreystephan.com/void-dwl/
<br> this article provided a lot of useful information

# TO DO / TO ADD
I still need to add my foot, yazi, and neovim config. These aren't really naything crazy, but I want to add these for my personal convenience.
