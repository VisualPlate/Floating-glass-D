# Floating-glass-D

**Floating-glass-D** is a dark, modern glass-like theme for the Cinnamon desktop environment. It features subtle transparencies and pronounced shadows designed to make application windows and content pop out from the background. This theme uses assets from Mint-Y Theme

## Theme details

| Component | Theme |
|-----------|-------|
| **Cinnamon Theme** | Floating-glass-D |
| **GTK Theme** | Floating-glass-D |
| **Window Border (Metacity)** | Floating-glass-D |
| **Recommended Icon Theme** | Mint-Y |
| **Recommended Cursor Theme** | DMZ-Black |
| **Button Layout** | `:minimize,maximize,close` (right-aligned) |

## Installation

### 1. Extract or move the folder

Move or extract the `Floating-glass-D` folder into your local themes directory:

```bash
mkdir -p ~/.themes
cp -r Floating-glass-D ~/.themes/
```

Alternatively, move it to `/usr/share/themes/` to make it available system-wide (requires `sudo`).

### 2. Apply the theme

Open **System Settings → Themes**, then apply the following:

- **Desktop:** `Floating-glass-D`
- **Applications (GTK):** `Floating-glass-D`
- **Window borders:** `Floating-glass-D`

Set the following additional themes:

- **Icons:** `Mint-Y`
- **Pointer:** `DMZ-Black`

## Customization

To adjust the title bar button layout to match the preset included in this package (`:minimize,maximize,close`), run the following command:

```bash
gsettings set org.cinnamon.desktop.wm.preferences button-layout ':minimize,maximize,close'
```

## License

Distributed under the **GPL-3.0 License**. See the `LICENSE` file for more information.