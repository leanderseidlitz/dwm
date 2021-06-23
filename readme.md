# DWM patch set and config
Works on dwm 6.2

## patches
The patch is the conflict-resolved merge of
- https://dwm.suckless.org/patches/systray/
- https://dwm.suckless.org/patches/clientindicators/
- https://dwm.suckless.org/patches/pertag/

## config
Config is inspired by https://github.com/schachmat/dwm/

# Usage
On gentoo, use +savedconfig, 
- place `dwm-6.2` into `/etc/portage/savedconfig/x11-wm/`
- place `systray_perworkspacelayout_clientindicators.patch` into `/etc/portage/patches/x11-wm/dwm-6.2`
