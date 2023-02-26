# stiedos-hypr

#![Screenshot](https://github.com/onerealti/raw/stiedos-hypr/)

## Install

### Yay

Run as user NOT ROOT!

```
# Before this you need base-devel installed
git clone https://aur.archlinux.org/yay-bin
cd yay-bin
makepkg -si
```

### Packages

``` bash
yay -S hyprland-bin polkit-gnome ffmpeg viewnior thunar starship wl-clipboard swaybg grimblast-git ffmpegthumbnailer playerctl noise-suppression-for-voice thunar-archive-plugin kitty waybar-hyprland wlogout swaylock-effects sddm-git nwg-look-bin papirus-icon-theme dunst illum-git rofi-lbonn-wayland-git aritim-dark-gtk-git pulseaudio pulseaudio-bluetooth pamixer firefox-beta-bin brightnessctl android-tools
```

## Gotchas

- Recommend archinstall with Sway as desktop for base
- SDDM-GIT is required or you will run into shutdown bugs and delays
- SDDM needs to be configured for autologin (recommend using swaylock on start of script for security)
- Replace xdg-desktop-portal-wlr with **[xdg-desktop-portal-hyprland-git](https://wiki.hyprland.org/hyprland-wiki/pages/Useful-Utilities/Hyprland-desktop-portal/)**

## Bugs

- Hyprland is still in beta (v0.22beta) as of the creation of these dot files

## Work In Progress

- [ ] Wayland guide for nwg-look, wlr-randr, etc.
- [ ] Synergy Workaround - Looking at waynergy or just using KVM
- [ ] Gamescope Addition - Adding more parity with Steamdeck features
- [x] More Customizations for Waybar - Battery, Backlight, etc.
- [ ] Auto-configuration

## Sources used making these

- Official Hyprland Github <https://github.com/hyprwm/Hyprland>
- Linux Mobiles Hyprland dot files <https://github.com/linuxmobile/hyprland-dots>
- Chris Titus Hyprland Files <https://github.com/ChrisTitusTech/hyprland-titus>
