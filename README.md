# My Arch Linux Dotfiles

Welcome to my personal dotfiles repository! This repository contains the configuration files for my Arch Linux setup. These are tailored to my workflow and preferences. Feel free to explore and adapt them for your own use.

---

## Applications & Configurations

### Hyprland
A lightweight and customizable Wayland compositor. Configurations are in the `hyprland/` folder.

![Hyprland Preview](preview/preview.png)

### Waybar
A highly customizable status bar for Wayland. Configurations are in the `waybar/` folder.

![Waybar Preview](waybar/preview.png)

### Hyprlock
A minimal and elegant screen locker. Configurations and assets are in the `hyprlock/` folder.

![Hyprlock Preview](preview/hyprlock.png)

### Kitty
A fast, feature-rich, and GPU-accelerated terminal emulator. Configurations are in the `kitty/` folder.

![Kitty Preview](kitty/preview.png)

### Neovim
A hyperextensible Vim-based text editor. Configurations are in the `nvim/` folder.

![Neovim Preview](nvim/preview.png)

### Alacritty
A simple, GPU-accelerated terminal emulator. Configurations are in the `alacritty/` folder.

![Alacritty Preview](alacritty/preview.png)

### Dunst
A lightweight notification daemon. Configurations are in the `dunst/` folder.

![Dunst Preview](dunst/preview.png)

---

## Installation
To use these configurations, clone the repository and symlink the desired configurations to your home directory.

```bash
git clone https://github.com/Llunatics/dotfiles.git
cd dotfiles
# Example: Symlink Hyprlock config
ln -s $(pwd)/hyprland ~/.config/hyprland
```

---

## Preview
Here's an overall look at my desktop setup:

![Desktop Preview](preview/desktop.png)

---

## Notes
- These dotfiles are constantly evolving as I tweak my setup.
- Designed for use on Arch Linux with Hyprland.

---

## License
This repository is under the MIT License. Feel free to use and modify these files to suit your needs.
