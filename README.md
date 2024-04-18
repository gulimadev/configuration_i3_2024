NEED THIS PROGRAMS
pcmanfm
dmenu
ranger
feh
nitrogen
xorg-init
i3-status
i3-wm
i3-lock
bluetoothctl
arc-gtk-theme
lxappearance
xf86-video-intel
libva-intel-driver

sudo vim /etc/X11/xorg.conf.d/20-intel.conf


Section "Device"
    Identifier  "Intel Graphics"
    Driver      "intel"
    Option      "TearFree"    "true"
    Option      "DRI"         "3"
EndSection
