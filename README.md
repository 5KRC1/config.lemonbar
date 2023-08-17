# getting hardware info
Wifi & ethernet: nmcli device
bluetooth: hcitool dev
battery: upower -e
monitor: Xrandr -q | grep -a "connected"
