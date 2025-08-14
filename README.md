# Project Purple – KDE Global Theme

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

---

## 📜 License
This project is licensed under the **GPL-3.0 License** – see [LICENSE](LICENSE) for details.

---

## 💖 Support Development
If you enjoy Project Purple, consider supporting me via PayPal:  
**[jones.lm89@gmail.com](mailto:jones.lm89@gmail.com)**
