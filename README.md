# 🐧 Arch Linux Dotfiles

My personal Arch Linux setup using Hyprland.

## ✨ Features

- 🪟 **Hyprland** → modern and efficient window manager
- 📊 **Waybar** → fully customizable status bar
- 🐚 **Zsh** → powerful and productive shell
- ⚡ **Oh My Zsh** → framework for customizing Zsh
- 🖼️ **Hyprpaper** → program for setting wallpapers
- 🔧 **Personalized aliases** → shortcuts to speed up commands
- 💻 **Terminal Settings** → optimized development environment
- 🚀 **Productivity scripts** → automations for faster workflow and scripts for productivity

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ebcdcf6e-3c1f-41a6-b11c-ebadb43cb0b1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a9ebc155-1220-4891-bde8-9c54ae615d37" />



## 📦 Installing dependencies

Before applying the dotfiles, install the necessary packages:

## 📦 Installing dependencies

## 📦 Installing dependencies

```bash
sudo pacman -S hyprland hyprpaper waybar kitty nautilus zsh blueman bluez bluez-utils swaync fastfetch ttf-jetbrains-mono-nerd
```

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

📥 Dotfiles Installation
Clone the repository:

```bash
git clone git@github.com:notoriouswin/archlinux-mydotfile.git
cd archlinux-mydotfile
cp -r . ~/
```


## 🎨 Customization


### Wallpaper

To change the wallpaper, simply modify the image used by Hyprpaper in the Hyprland/Hyprpaper configuration directory.


```bash
~/.config/hypr/hyprpaper.conf
```

Simply set monitor, image and cover mode.


## ⚙️ Extras in the terminal

- **cmatrix**: start like this for blue theme (`cmatrix -C blue`)
- **tty-clock**: start like this for blue theme, seconds, and time in center (`tty-clock -c -s -C 4`).
- **Zsh plugins and shortcuts**:
  - `Alt + C` → opens a quick menu of folders for navigation.
  - `Ctrl + R` → search the command history.
  - `google <what you want to search>` to open a Google search directly from the terminal.



## 🚀 Objective

Keeping my Arch Linux settings organized, versioned, and easy to restore on any machine.

## 🤝 Contributions

Feel free to open Issues or Pull Requests with improvements and suggestions.

## 📄 License

MIT License
