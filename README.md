# dotfile
the dotfile that potato use
# <img src="assets/icon.png" width="30" height="30"> My Dotfiles

**Clean • Productive • Customized**  
*A curated collection of my development environment configurations*

## 🖼️ Visual Showcase

| Work Environment | Login Screen |
|------------------|--------------|
| [![onwork](screenshots/onwork.png)](screenshots/onwork.png) | [![sddm](screenshots/sddm.png)](screenshots/sddm.png) |
| **Main Desktop** | **Alternative View** |
| [![main](screenshots/main.png)](screenshots/main.png) | [![main1](screenshots/main1.png)](screenshots/main1.png) |

<div align="center">
  <img src="screenshots/onwork.png" width="45%">
  <p style="color:#888; font-size:0.9em;">My productive coding environment</p>
</div>
<img src="screenshots/main.png" style="transition:transform 0.3s;" onmouseover="this.style.transform='scale(1.02)'" onmouseout="this.style.transform='scale(1)'">

## ✨ Features
- **Terminal Powerhouse**: Zsh with [Starship](https://starship.rs) prompt + [zinit](https://github.com/zdharma-continuum/zinit) plugins
- **Editor Mastery**: Neovim Lua config with LSP, debugging, and 50+ plugins
- **WM Integration**: [i3-gaps](https://github.com/Airblader/i3) / [Hyprland](https://hyprland.org/) configurations
- **Cross-OS**: Works on Linux/macOS with conditional loading
- **One-shot Setup**: Single command installation

## ⚙️ Included Configurations
| Component       | Highlights                              |
|-----------------|-----------------------------------------|
| **Neovim**      | LSP, Treesitter, Telescope, Debug Adapters |
| **Tmux**        | Sessions persistence, TPM plugins, theming |
| **Shell**       | Zsh + Oh-My-Zsh, custom aliases/functions |
| **WM/DE**       | i3/Hyprland keybinds, autostart scripts |
| **Terminal**    | Alacritty/Kitty themes & settings       |
| **Tools**       | Git, GDB, Bat, Fzf, system utilities    |

## 🚀 Installation
```bash
# Clone with submodules
git clone --recursive https://github.com/yourusername/dotfiles.git ~/.dotfiles

# Run installer
cd ~/.dotfiles && ./install
