# Atmospheres

A collection of dark themes for VS Code — each one built around a specific mood, palette, or world. From warm earthy tones to game-inspired designs, there's something here for everyone who spends a lot of time staring at code.

---

## Themes

| Theme | Vibe |
|---|---|
| **Terra** | Warm browns, burnt orange, sandstone — like coding by a campfire |
| **Moss & Stone** | Deep forest greens, sage, dark lichen — grounded and quiet |
| **Volcanic** | Obsidian black, lava orange, sulfur yellow — intense and fiery |
| **Bioluminescence** | Deep navy, electric cyan — midnight ocean glow |
| **Midnight Library** | Dark indigo, amber warmth — late nights and old books |
| **Copper & Verdigris** | Bronze darks, copper orange, oxidized teal — antique metal |
| **Smoked Amethyst** | Smoky purple-gray, soft lavender — quiet and elegant |
| **Crimson Linen** | Dark wine backgrounds, cream foreground, deep crimson accents |
| **Deep Jade** | Near-black forest green, sage mint, pale seafoam |
| **Rose Quartz** | Deep mauve, dusty rose — soft without being distracting |
| **Detroit — Connor** | CyberLife navy, thirium cyan strings, DEVIANT teal, stress red |
| **Detroit — Kara** | Deep purple-gray, lavender LED, warm pink and teal |
| **Detroit — Markus** | Dark charcoal, gold LED, revolution red — bold and defiant |
| **The Last of Us** | Overgrown dark green, amber warmth, fungal undertones |
| **Adventure Time** | Night sky blue, candy yellow, cotton candy pink |
| **Rick and Morty** | Space black, portal green, interdimensional purple |
| **Stardew Valley** | Harvest gold, wizard purple, river blue, spring flower pink |
| **1-Bit** | Pure black and white — no color, maximum focus |
| **Coffee** | Espresso dark, cream foreground, caramel and latte accents |
| **GTA** | Urban asphalt, wanted-star red, neon green, gold |
| **Half Life** | Industrial concrete, lambda orange, Xen alien green, Combine blue |
| **Cherry Cola** | Deep cola red, cherry highlight, dark fizz |
| **God of War** | Ashen dark, Spartan red, Norse gold |

---

## How to Install

### From the VS Code Marketplace
1. Open VS Code
2. Go to the Extensions panel (`Ctrl+Shift+X`)
3. Search for **Atmospheres**
4. Click Install

### From a VSIX file
1. Download the `.vsix` from the [Releases](https://github.com/SinglaRijul/vs-code-themes/releases) page
2. Open VS Code
3. Press `Ctrl+Shift+P` and type **Install from VSIX**
4. Select the downloaded file

### From source
```bash
git clone https://github.com/SinglaRijul/vs-code-themes.git
cd vs-code-themes
```
Then copy the folder into your VS Code extensions directory:
- **Windows:** `%USERPROFILE%\.vscode\extensions\`
- **macOS / Linux:** `~/.vscode/extensions/`

---

## Switching Themes

Press `Ctrl+K Ctrl+T` to open the theme picker, or:

1. Press `Ctrl+Shift+P`
2. Type **Color Theme**
3. Pick any theme from the list

---

## Publishing (for reference)

```bash
npm install -g @vscode/vsce
vsce login salad-crunch
vsce package
vsce publish
```

---

## License

MIT © SinglaRijul
