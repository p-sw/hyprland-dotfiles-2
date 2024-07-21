# Hyprland Configuration v2

## Before Installation

### Note About NetworkManager

This configuration uses **networkmanager-dmenu** for easier control via rofi.  

> If you don't care

* Install NetworkManager

> Or, if you want to use other

* Just use what you want, and change the configuration for network module in **Waybar** to make it work with that.

### Note About Dependency Replacement

* Starship
  * Easily replaceable. You can just ignore if you don't want to use this.
* Rofi
  * Also easily replaceable. Just be careful when you use networkmanager-dmenu - you should change the configuration.
* _[TODO]_

### Requirements

* [Hyprland](https://hyprland.org) - Desktop environment
    * [hyprpaper](https://wiki.hyprland.org/Hypr-Ecosystem/hyprpaper/) - Wallpaper
    * [hypridle](https://wiki.hyprland.org/Hypr-Ecosystem/hypridle/) - Idle management
    * [hyprlock](https://wiki.hyprland.org/Hypr-Ecosystem/hyprlock/) - Screen lock
    * [xdg-desktop-portal-hyprland](https://wiki.hyprland.org/Hypr-Ecosystem/xdg-desktop-portal-hyprland/) - XDG Desktop Portal
    * [xdg-desktop-portal-gtk](https://wiki.hyprland.org/Useful-Utilities/xdg-desktop-portal-hyprland/#installing) - For file picker fallback of xdg-desktop-portal-hyprland
    * [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Wayland clipboard utilities
    * [grimshot](https://www.mankier.com/1/grimshot) - Screenshot tool
    * [Kitty](https://sw.kovidgoyal.net/kitty) - Shell used by Hyprland
* [Starship](https://starship.rs) - For shell customization
* [Rofi](https://github.com/davatorium/rofi) - Application launcher & dmenu replacement
* [Waybar](https://github.com/Alexays/Waybar) - Wayland bar
* [networkmanager-dmenu](https://github.com/firecat53/networkmanager-dmenu) - Easier control NetworkManager via Rofi
* [wlogout](https://github.com/ArtsyMacaw/wlogout) - Logout menu
* [dunst](https://github.com/dunst-project/dunst) - Notification
* [yazi](https://github.com/dunst-project/dunst) - Terminal File Manager

## Installation

1. Install requirements.
2. Move everything in .config to your ~/.config folder.
3. installed yay

## Shortcuts

**mainMod = Super (Windows key or (sorry idk mac keyboard))**

### Hyprland Features

* `mainMod` + `C`: Close active window
* `mainMod` + `F`: Toggle floating window
* `mainMod` + `Left Click`: Move window
* `mainMod` + `Right Click`: Resize floating window
* `mainMod` + `Tab`: Make window fullscreen

### Applications

* `mainMod` + `Q`: Open Kitty (shell)
* `mainMod` + `E`: Run Yazi (shell file explorer)
* `mainMod` + `Space`: Run Rofi (application launcher)
* `mainMod` + `L`: Run hyprlock (screen lock)

### Workspace

* `mainMod` + `Left / Right Arrow`: Switch to prev / next workspace
* `mainMod` + `Left Shift` + `Left / Right Arrow`: Switch to prev / next workspace with active window

### Screenshot (Grimshot)

* `PrintScreen`: Capture manually selected area, and copy it to clipboard
* `mainMod` + `PrintScreen`: Capture current active window, and copy it to clipboard
* `Left Ctrl` + `PrintScreen`: Capture manually selected area, and save it to home location.
* `Left Ctrl` + `mainMod` + `PrintScreen`: Capture current active window, and save it to home location.
