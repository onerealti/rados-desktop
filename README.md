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
yay -S hyprland polkit-gnome ffmpeg rofi thunar starship wl-clipboard wf-recorder swaybg grimblast-git ffmpegthumbnailer tumbler playerctl noise-suppression-for-voice thunar-archive-plugin kitty waybar-hyprland wlogout swaylock-effects sddm-git nwg-look-bin aritim-dark-gtk-git papirus-icon-theme dunst illum-git firefox-beta-bin brightnessctl android-tools android-file-transfer

fonts = otf-sora   \
ttf-nerd-fonts-symbols-common otf-firamono-nerd inter-font    \
ttf-fantasque-nerd noto-fonts noto-fonts-emoji ttf-comfortaa  \
ttf-jetbrains-mono-nerd ttf-icomoon-feather ttf-iosevka-nerd  \
adobe-source-code-pro-fonts
```

## Gotchas

- Recommend archinstall with Sway as desktop for base
- SDDM-GIT is required or you will run into shutdown bugs and delays
- SDDM needs to be configured for autologin (recommend using swaylock on start of script for security)
- Replace xdg-desktop-portal-wlr with **[xdg-desktop-portal-hyprland-git](https://wiki.hyprland.org/hyprland-wiki/pages/Useful-Utilities/Hyprland-desktop-portal/)**

## Bugs

- Hyprland is still in beta (0.2) as of the creation of these dot files
- Sometimes my RX5700XT goes to sleep and requires a reload, because it is stuck on black screen.

## Work In Progress

- [ ] Help Popup with Hotkey
- [ ] Wayland guide for nwg-look, wlr-randr, etc.
- [ ] Synergy Workaround - Looking at waynergy or just using KVM
- [ ] Gamescope Addition - Adding more parity with Steamdeck features
- [x] More Customizations for Waybar - Battery, Backlight, etc.
- [ ] Auto-configuration - Long term goal

## Sources used making these

- Official Hyprland Github <https://github.com/hyprwm/Hyprland>
- Linux Mobiles Hyprland dot files <https://github.com/linuxmobile/hyprland-dots>
