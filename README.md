# RadOS Desktop

## Install

- **[Arch Linux](https://archlinux.org)** with Sway as DE
### **[Yay](https://github.com/Jguer/yay)**

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
udiskie   \
ntfs-3g   \
illum-git   \ 
brightnessctl   \ 
android-sdk-platform-tools   \ 
android-file-transfer   \

fonts = otf-sora   \
ttf-nerd-fonts-symbols-common otf-firamono-nerd inter-font    \
ttf-fantasque-nerd noto-fonts noto-fonts-emoji ttf-comfortaa  \
ttf-jetbrains-mono-nerd ttf-icomoon-feather ttf-iosevka-nerd  \
adobe-source-code-pro-fonts
```

### **[Bluetooth Headset](https://wiki.archlinux.org/title/bluetooth_headset)**

``` bash
pulseaudio-bluetooth
bluez
bluez-utils
```

## Imps

- **[Sound Open Firmware](https://github.com/thesofproject/sof-bin)**
- Replace xdg-desktop-portal-wlr with **[xdg-desktop-portal-hyprland-git](https://wiki.hyprland.org/hyprland-wiki/pages/Useful-Utilities/Hyprland-desktop-portal/)**
- chmod +x ~/.config/hypr/xdg-portal-hyprland
- chmod +x ~/.config/waybar/scripts/waybar-wttr.py

## Note

- Hyprland is still in beta (v0.24.1) as of latest commit.

## In Progress

- [ ] Auto-configuration
- [ ] Full fledged daily driver

## Sources

- **[Hyprland on Github](github.com/hyprwm/Hyprland)**
- **[Linux Mobiles Hyprland dot files](https://github.com/linuxmobile/hyprland-dots)**
- **[Chris's config files](https://github.com/ChrisTitusTech/hyprland-titus)**
