# 🌌 Arch-Hyprland: Theoretical Physics & C++ Environment

A deterministic, high-performance Wayland configuration optimized for the **Intel Core Ultra 5** (Meteor Lake) architecture. This "rice" prioritizes a distraction-free workflow for mathematical modeling and software engineering.

## 🛠 Technical Specifications
* **Kernel:** Arch Linux (Rolling)
* **Compositor:** [Hyprland](https://hyprland.org/) (Dynamic Tiling)
* **Status Bar:** Waybar (Custom CSS)
* **Terminal Emulator:** Kitty (GPU-accelerated)
* **Shell & Fetch:** Bash & Fastfetch
* **Visualizer:** Cava (Audio spectrum)

## 🏗 System Architecture (Migration)
This repository utilizes **GNU Stow** to manage symbolic links. This ensures that the environment is "hardware-agnostic"—it can be deployed on any machine with minimal friction.

### Deployment Protocol:
1. **Synchronize Repository:**
   `git clone https://github.com/luckygangwar/dotfiles.git ~/dotfiles`

2. **Establish Symbolic Links:**
   `cd ~/dotfiles && stow -R cava kitty Thunar waybar hypr dunst fastfetch`

## 📜 Philosophical Rigor
The configuration follows a modular design pattern. By decoupling the dotfiles from the `~/.config` directory via symlinks, we maintain a clean separation between user data and system state. No sugarcoating, no bloat—just the necessary logic for a functional workspace.

---
*Created by Lucky Gangwar | 2026*
