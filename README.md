# wm
my dwl setup <br>
patches are inside the folders.<br>

i'm not really sure how usable this is for everyone since idk how to make a proper dots repo, but im trying my best!!!!!!!!!!! im just trying to make it easier for me if i reinstall or something

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

# dots

foot is configured for transparency and the gruvbox material soft theme<br><br>
yazi is configured slightly to have smart enter and neovim as the default editor <br><br>
nvim: this is a bit controversial, but it's basically a slightly modified version of lazyvim. I know I should probably make a config from scratch at some point, but... not now. im lazy........................ <br><br>




# Dependencoes
I'm missing a few so give me some time to update. Luckily, the compile errors should be verbose enough for you to figure it out though  <br>

```
xbps-install libinput libinput-devel wayland wayland-devel wlroots0.19 wlroots0.19-devel libxkbcommon libxkbcommon-devel wayland-protocols pkg-config xorg-server-xwayland brightnessctl tllist fcft pixman pipewire wireplumber nerd-fonts font-hack-ttf alsa-pipewire swaybg wl-clipboard elogind dbus
```

<br><br>

# CREDITS:
https://www.coreystephan.com/void-dwl/
<br> this article provided a lot of useful information

