# Project Purple – KDE Global Theme

[![Latest Release](https://img.shields.io/github/v/release/Robotminded/ProjectPurple?display_name=tag)](https://github.com/Robotminded/ProjectPurple/releases)
[![Stars](https://img.shields.io/github/stars/Robotminded/ProjectPurple)](https://github.com/Robotminded/ProjectPurple/stargazers)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](./LICENSE)
[![Website](https://img.shields.io/badge/Website-robotminded.github.io-informational)](https://robotminded.github.io)

Minimal. Neon. Unmistakably Purple.  
A polished KDE Plasma Global Theme designed for a sleek, futuristic look with strong contrast, glowing accents, and a signature purple aesthetic.

---

## ✨ Features
- **Complete KDE Global Theme** (colors, plasma style, window decorations, wallpaper)  
- **One-click install script** for easy setup  
- **Matching Aurorae window decoration** for a consistent look  
- **High-contrast color scheme** optimised for readability  
- **Custom wallpaper** included  
- Works with **KDE Plasma 5 & 6**  
- **Neon purple accent colors** with glowing UI effects  
- **Transparent panels** for a futuristic aesthetic  
- **Rounded, high-contrast icons**  
- **Minimalist cursor theme** with neon outline  
- Optimized for **developer virtual machines**  

---

## 📸 Screenshots
| Desktop | Window Decoration |
|---------|-------------------|
| ![Desktop Preview](screenshots/desktop.png) | ![Window Decoration](screenshots/decorations.png) |

---

## 📦 Installation
1. **Download** the latest release ZIP from [Releases](../../releases/latest).  
2. **Extract** the ZIP file anywhere.  
3. **Open Terminal** in the extracted folder.  
4. Run:
   ```bash
   bash install.sh
   ```
5. Log out and log back in to ensure all changes apply.  

---

## 🛠 Manual Installation (Advanced)
- Copy `org.projectpurple` to:
  ```
  ~/.local/share/plasma/look-and-feel/
  ```
- Copy `ProjectPurple` (Aurorae) to:
  ```
  ~/.local/share/aurorae/themes/
  ```
- Copy the wallpaper to:
  ```
  ~/.local/share/wallpapers/
  ```
- Apply via **System Settings → Appearance**.  

---

## 💡 Tips
- After applying the theme, if **window decorations** do not update automatically, run:
  ```bash
  qdbus org.kde.KWin /KWin reconfigure
  ```
- Pair with the [**Project Purple Wallpapers**](https://github.com/Robotminded/ProjectPurpleWallpapers) for a complete desktop experience.  
- Works seamlessly in **UTM virtual machines** on macOS.  

---

## 🗺 Roadmap
- [ ] Additional Aurorae window decorations  
- [ ] Extended GTK states (hover, pressed, disabled)  
- [ ] Additional cursor variants  
- [ ] Dark + Light wallpaper bundle  
- [ ] Gumroad + GNOME-Look releases for wider distribution  

---

## 📜 License
This project is licensed under the **GNU General Public License v3.0** – see [LICENSE](LICENSE) for details.  

© 2025 Robotminded — free software for a futuristic desktop.  

---

## 💖 Support Development
If you enjoy Project Purple, consider supporting me via PayPal:  
👉 [**paypal.me/Robotminded**](https://www.paypal.me/Robotminded)
