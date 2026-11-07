# DTCode Theme

A VS Code color theme based on the design system of [DTCode — Blog lập trình](https://www.dtcode.io.vn/): cream paper, navy ink, red accents.

## Variants

| Theme | Background | Text | Accent |
|---|---|---|---|
| **DTCode Light** | `#F5EFE0` cream | `#35426E` navy | `#C83538` red |
| **DTCode Dark** | `#000000` black | `#F5EFE0` cream | `#F0706A` light red |

All editor text colors meet WCAG 2.2 AA contrast (≥ 4.5:1) against the editor background.

## Installation

**From the Marketplace:** open the Extensions view (`Ctrl+Shift+X`), search for **DTCode Theme**, and click **Install**.

**From a `.vsix` file:** run `Extensions: Install from VSIX...` from the Command Palette and pick the file.

## Activate

`Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`) → select **DTCode Light** or **DTCode Dark**.

## Recommended font (vintage newspaper style)

Themes can't change fonts. Add this to your `settings.json` (`Ctrl+Shift+P` → `Preferences: Open User Settings (JSON)`):

```json
"editor.fontFamily": "'Courier Prime', 'Courier New', monospace",
"editor.fontSize": 15,
"editor.lineHeight": 1.6,
"editor.letterSpacing": 0.3,
"terminal.integrated.fontFamily": "'Courier Prime', 'Courier New', monospace"
```

[Courier Prime](https://fonts.google.com/specimen/Courier+Prime) is free. If it isn't installed, VS Code falls back to Courier New.

## Syntax palette

| Element | Light | Dark |
|---|---|---|
| Keyword, tag | `#B42E31` | `#F0706A` |
| String | `#2F6B3A` | `#9CCB8A` |
| Number, constant | `#9A4A0B` | `#F0A35E` |
| Function | `#2B5BA8` | `#8FB2F0` |
| Type, class | `#1F6A75` | `#6CC5C9` |
| Property | `#5A3F8C` | `#C3A6F0` |
| Comment | `#6B6656` | `#8C8678` |

## Development

Open the `dt-theme` folder in VS Code and press `F5` (or pick **Run DTCode Theme** in Run and Debug). Theme changes reload live in the `[Extension Development Host]` window.

```
dt-theme/
├── package.json
└── themes/
    ├── dtcode-light-color-theme.json
    └── dtcode-dark-color-theme.json
```
