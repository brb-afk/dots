# Dotfiles
Personal configuration files. Always messy, sometimes documented.

---

## Screenshots

![archlinux scrot](/screenshots/screenshot.png?raw=true "archlinux Screenshot")

---

## Setup

### EndevourOS

* WM: [ hyprland-nvidia-hidpi-git ](https://aur.archlinux.org/packages/hyprland-nvidia-hidpi-git)
* Bar: [ waybar-hyprland-git ](https://aur.archlinux.org/packages/waybar-hyprland-git) 
* Terminal: [ alacritty ](https://aur.archlinux.org/packages/alacritty-git/)
* Run dialog, etc: [ wofi ](https://archlinux.org/packages/community/x86_64/wofi/)
* Screenshot tool: [ grimblast-git ](https://aur.archlinux.org/packages/grimblast-git)
* AUR Package Manager: [ yay ](https://aur.archlinux.org/packages/yay)
* Color scheme: managed by [ gradience ](https://aur.archlinux.org/packages/gradience)
* Font: Fantasque Sans Mono

---

# OS Install 
Install EndevourOS - 
- Online installation
- Select no desktop environment
- Untick X options

On first boot, perform  the following:

````shell
git clone https://github.com/craio/dots.git
````

```shell
./dots/scripts/.config/scripts/install
```