# Collective OS "Shades of Jade" Theme
This repository (https://github.com/gwenphalan/collective-os-theme/) packages the default "Shades of Jade" theme that ships with Collective OS, my customized fork of Omarchy. It keeps the deep jade palette from the upstream project while tuning contrast, icons, and wallpapers for the Collective OS desktop.

## Origin
Forked from HANCORE-linux's Omarchy Shades of Jade theme: https://github.com/HANCORE-linux/omarchy-shadesofjade-theme. Collective OS layers in its own UI tweaks, wallpapers, and launcher styling on top of that base.

## Installation
### Using the Collective OS helpers
```bash
collectiveos-theme install https://github.com/gwenphalan/collective-os-theme.git
```

### Manual install
```bash
git clone https://github.com/gwenphalan/collective-os-theme.git
cd collective-os-theme
./install.sh
```

## VS Code Theme
- Reuse the VS Code flavor from https://github.com/Justikun/omarchy-osaka-jade-theme/blob/main/vscode.json

## Neovim Theme
- Uses https://github.com/bjarneo/pixel.nvim to mirror the terminal palette.<br>
- Keep LazyVim updated with `:Lazy sync` so highlights stay fresh.<br>

## Waybar Theme
Styling inspiration and supplemental widgets come from https://github.com/HANCORE-linux/Waybar-Theme-red-accents-.git

### License
MIT
