
# Vesper Theme for Ghostty

A minimal yet vibrant **Ghostty** terminal theme inspired by the **Vesper** VSCode theme. It features a **dark background** with **warm and cool highlights** for a balanced and modern look.

## 🎨 Theme Preview

> **Colors inspired by Vesper's syntax highlighting:**
> - **Background:** `#101010`
> - **Foreground:** `#ffffff`
> - **Accent Colors:** Orange (`#ffc799`), Aqua (`#99ffe4`)


![Vesper Theme Preview]([https://your-image-link.com](https://raw.githubusercontent.com/beingfranklin/vesper-ghostty/refs/heads/main/Screenshot.png)) 

## 📥 Installation

1. **Download the theme**:
   ```sh
   git clone https://github.com/beingfranklin/vesper-ghostty.git
   cd vesper-ghostty
   ```

2. **Move the theme to Ghostty's theme directory**:
   ```sh
   mkdir -p ~/.config/ghostty/themes
   cp Vesper.conf ~/.config/ghostty/themes/
   ```

3. **Set the theme in Ghostty**:
   Open `~/.config/ghostty/config` and add:
   ```ini
   theme = vesper
   ```

4. **Restart Ghostty** to apply the theme:
   ```sh
   ghostty --reload
   ```

## 🎨 Color Palette

| Color Name       | Hex Code  | Usage            |
|-----------------|----------|------------------|
| **Background**  | `#101010` | Terminal BG      |
| **Foreground**  | `#ffffff` | Main Text        |
| **Cursor**      | `#ffc799` | Cursor           |
| **Selection**   | `#2a2a2a` | Selection BG     |
| **Orange**      | `#ffc799` | Keywords, Numbers |
| **Aqua**        | `#99ffe4` | Strings, Functions |

## 🛠️ Customization

Feel free to tweak the color scheme inside `vesper.conf` to match your preferences.

## 📝 License

This theme is licensed under the [MIT License](LICENSE).

## 💙 Credits

- Inspired by **[Vesper for VSCode](https://github.com/raunofreiberg/vesper)**
- Terminal adaptation for **[Ghostty](https://ghostty.org/)** by **[Franklin](https://github.com/beingfranklin)**

---



This README is **ready for GitHub** with installation steps, a color palette table, and credits. Let me know if you need any tweaks! 🚀

Enjoy using Vesper for Ghostty! 🚀
