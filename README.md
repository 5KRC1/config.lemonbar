<<<<<<< HEAD
# getting hardware info
Wifi & ethernet: nmcli device
bluetooth: hcitool dev
battery: upower -e
monitor: Xrandr -q | grep -a "connected"
=======
# Lemonbar configuration
---

## Setup
1. Clone this directory to ~/.config/ and rename it to lemonbar
2. Ensure that required packages are installed.
3. Make sure panel, panel_bar and dunst-history are all executable.
4. Move panel file to `~/.local/bin`.
5. Either manually run panel file or add it to wm's config as `panel $`


## Requiremets
- ![nmcli](https://wiki.archlinux.org/title/NetworkManager) (network)
- ![hcitool](https://wiki.archlinux.org/title/Bluetooth) (bluetooth)
part of ![bluez-utils-compat](https://aur.archlinux.org/packages/bluez-utils-compat)
- ![upower](https://wiki.archlinux.org/title/Power_management) (battery)
- ![Xrandr](https://wiki.archlinux.org/title/Xrandr) (monitors)
- ![dunst](https://github.com/dunst-project/dunst) (notifications)
- ![conky](https://wiki.archlinux.org/title/Conky) (cpu, ram, clock)
- ![alsamixer](https://wiki.archlinux.org/title/Advanced_Linux_Sound_Architecture) (sound)
- ![xtitle](https://aur.archlinux.org/packages/xtitle) (window title)
- ![bspwm](https://wiki.archlinux.org/title/Bspwm) (wm)
- ![trayer](https://man.archlinux.org/man/extra/trayer/trayer.1.en) (minimized apps)

hcitool is deprecated and will have to be replacedhttps://man.archlinux.org/man/extra/trayer/trayer.1.en.
>>>>>>> 026892e (readme)
