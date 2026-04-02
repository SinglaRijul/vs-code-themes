# Earthy Themes for VS Code

Two handcrafted dark themes inspired by soil, clay, moss, stone, and forest floors — warm and grounding to code in.

---

## Themes

### Terra
A **warm earthy** palette built around burnt oranges, clay, sandstone, and deep brown backgrounds. Feels like working by firelight in a desert canyon.

| Element        | Color Preview | Hex       | Description         |
|----------------|---------------|-----------|---------------------|
| Background     | 🟫            | `#1c1209` | Deep walnut brown   |
| Keywords       | 🟧            | `#d4693a` | Burnt orange        |
| Strings        | 🟨            | `#c8a850` | Warm sandstone      |
| Functions      | 🟤            | `#c87b5a` | Terracotta          |
| Comments       | ⬛            | `#6a5038` | Dark umber          |
| Numbers        | 🟡            | `#c49740` | Ochre               |

---

### Moss & Stone
A **cool earthy** palette built around sage greens, fern, lichen, and dark forest backgrounds. Feels like coding in a mossy stone alcove.

| Element        | Color Preview | Hex       | Description         |
|----------------|---------------|-----------|---------------------|
| Background     | 🟩            | `#0e1a0f` | Deep forest black   |
| Keywords       | 🟢            | `#6aaa60` | Sage green          |
| Strings        | 💚            | `#a0b850` | Golden moss         |
| Functions      | 🔵            | `#5aaa8a` | Seafoam fern        |
| Comments       | ⬛            | `#3e6040` | Dark lichen         |
| Numbers        | 🟡            | `#b0a040` | Amber moss          |

---

## Installation

### From VS Code Marketplace
1. Open VS Code
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Type `ext install your-publisher-name.earthy-themes`
4. Press Enter

### From VSIX (Manual)
1. Download the `.vsix` file from [Releases](https://github.com/your-username/vscode-earthy-themes/releases)
2. Open VS Code
3. Press `Ctrl+Shift+P` → type **"Install from VSIX"**
4. Select the downloaded file

### From Source
```bash
git clone https://github.com/your-username/vscode-earthy-themes.git
cd vscode-earthy-themes
```
Then copy the folder to your VS Code extensions directory:
- **Windows:** `%USERPROFILE%\.vscode\extensions\`
- **macOS/Linux:** `~/.vscode/extensions/`

Or open the folder in VS Code and press `F5` to launch the Extension Development Host.

---

## Activating the Theme

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
2. Type **"Color Theme"** → select **Preferences: Color Theme**
3. Choose **Terra** or **Moss & Stone**

Or via the keyboard shortcut: `Ctrl+K Ctrl+T`

---

## GitHub Setup

### First-time setup
```bash
git init
git add .
git commit -m "Initial commit: Earthy Themes v1.0.0"
git branch -M main
git remote add origin https://github.com/your-username/vscode-earthy-themes.git
git push -u origin main
```

### Subsequent pushes
```bash
git add .
git commit -m "your message"
git push
```

---

## Publishing to the VS Code Marketplace

### Prerequisites
```bash
npm install -g @vscode/vsce
```

### Steps
1. Create a publisher account at [marketplace.visualstudio.com](https://marketplace.visualstudio.com/manage)
2. Generate a Personal Access Token (PAT) in Azure DevOps
3. Update `package.json` — replace `"your-publisher-name"` with your actual publisher ID
4. Login and publish:
```bash
vsce login your-publisher-name
vsce package        # creates a .vsix file
vsce publish        # publishes to the marketplace
```

---

## Project Structure

```
vscode-earthy-themes/
├── themes/
│   ├── terra-color-theme.json       # Warm earthy theme
│   └── moss-stone-color-theme.json  # Cool mossy theme
├── package.json                     # Extension manifest
├── .vscodeignore                    # Files excluded from package
├── .gitignore
├── CHANGELOG.md
└── README.md
```

---

## Contributing

Pull requests are welcome! If you'd like to suggest a color adjustment or report an issue:

1. [Open an issue](https://github.com/your-username/vscode-earthy-themes/issues)
2. Fork the repo and create a branch
3. Make your changes to the theme JSON files
4. Submit a pull request

---

## License

MIT © Your Name
