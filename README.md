# RadOS Desktop

#![Screenshot](https://github.com/onerealti/raw/main/rados-hypr.png)

## Install

### Installing **[Yay](https://github.com/Jguer/yay)**

```
$ pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```

### Packages

``` bash
yay -S

hyprland   \
polkit-kde-agent   \
ffmpeg   \
rofi   \
pavucontrol   \
thunar   \
starship   \
wl-clipboard   \
wf-recorder   \
swaybg   \
grimblast-git   \
ffmpegthumbnailer   \
tumbler   \
playerctl   \
kitty   \ 
waybar-hyprland   \ 
wlogout   \ 
swaylock-effects   \ 
sddm-git   \
pamixer   \
nwg-look-bin   \ 
aritim-dark-gtk-git   \ 
papirus-icon-theme   \ 
dunst   \ 
illum-git   \ 
brightnessctl   \ 
android-tools   \ 
android-file-transfer   \

fonts = otf-sora   \
ttf-nerd-fonts-symbols-common otf-firamono-nerd inter-font    \
ttf-fantasque-nerd noto-fonts noto-fonts-emoji ttf-comfortaa  \
ttf-jetbrains-mono-nerd ttf-icomoon-feather ttf-iosevka-nerd  \
adobe-source-code-pro-fonts
```

## Imps

- Recommended archinstall with Sway as DE
- Replace xdg-desktop-portal-wlr with **[xdg-desktop-portal-hyprland-git](https://wiki.hyprland.org/hyprland-wiki/pages/Useful-Utilities/Hyprland-desktop-portal/)**

## Note

- Hyprland is still in beta (v0.24.1) as of latest commit.

## In Progress

- [ ] Auto-configuration
- [ ] Full fledged daily driver

## Sources

- **[Hyprland on Github](github.com/hyprwm/Hyprland)**
- **[Linux Mobiles Hyprland dot files](https://github.com/linuxmobile/hyprland-dots)**
- **[Chris's config files](https://github.com/ChrisTitusTech/hyprland-titus)**
