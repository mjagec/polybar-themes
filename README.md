

# 💠 Polybar Themes – Custom Status Bars for Arch Linux

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)

A curated collection of personal Polybar configuration themes, refined over time on my Arch Linux setup. These aren't just configs—they're the result of hands-on Linux sysadmin tinkering: optimizing modules for performance, integrating media controls, and adapting layouts for different hardware. As I've leveled up my dotfiles game (think pacman deep dives, i3wm integrations, and font tweaks), these themes have evolved into lightweight, modular setups adapted to my workflow.

> *"Polybar aims to help users build beautiful and highly customizable status bars for their desktop environment, without the need of a black belt in shell scripting."*  
> – [Polybar Docs](https://github.com/polybar/polybar)

## 🎨 Featured Themes
- **Laptop Minimalist**: Compact layout for on-the-go—CPU, memory, battery, and Spotify glances. Perfect for ultrabooks.
- **Ultrawide Productivity**: Expanded modules for multi-monitor chaos—weather feeds, scrolling workspaces, and system stats at a glance.

Each theme includes commented `config.ini` files, launch scripts, and module snippets for easy adaptation.

## 📸 Screenshots
<img width="1710" height="719" alt="image" src="https://github.com/user-attachments/assets/fc14262d-3c90-4a1d-809c-1dc25f3d4316"/>

## 🛠 Dependencies
Tailored for Arch Linux (via AUR or official repos). Install with `pacman` or `yay`.

### Laptop Setup
- `playerctl` – Media controls  
- `zscroll` – Smooth scrolling text  
- `ttf-terminus` – Clean bitmap font  
- `nerd-fonts-(your-choice)` – Icons & glyphs (e.g., Hack Nerd Font)  
- `polybar-spotify` – Spotify module  

### Ultrawide Setup
- All laptop deps +  
- `openweather-module` – Dynamic weather display  

## 🚀 Quick Setup
1. Clone and navigate:  
   ```bash
   git clone https://github.com/mjagec/polybar-themes.git
   cd polybar-themes
