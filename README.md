# ChHsich Nerd Font - AUR Package

A custom Nerd Font combining ComicShannsMono's English characters with Maple Mono NF CN's Chinese support. Features 16 font variants with complete Unicode coverage.

## About

ChHsich Nerd Font is a custom font that combines:
- **ComicShannsMono Nerd Font** for English characters and symbols
- **Maple Mono NF CN** for Chinese character support

This font provides excellent support for both English and Chinese text, making it perfect for developers and users who work with multilingual content.

## Features

- 16 font variants (Regular, Bold, Italic, BoldItalic, Light, LightItalic, Medium, MediumItalic, SemiBold, SemiBoldItalic, ExtraBold, ExtraBoldItalic, Thin, ThinItalic, ExtraLight, ExtraLightItalic)
- Complete Unicode coverage
- Nerd Font icons support
- Chinese character support
- Optimized for programming and development

## Installation

### From AUR (Recommended)

```bash
# Using yay
yay -S chhsich-nerd-font

# Using paru
paru -S chhsich-nerd-font

# Using makepkg
git clone https://aur.archlinux.org/chhsich-nerd-font.git
cd chhsich-nerd-font
makepkg -si
```

### Manual Installation

1. Download the latest release from [GitHub Releases](https://github.com/ChHsiching/chhsich-nerd-font/releases)
2. Extract the ZIP file
3. Copy the font files to your system:
   ```bash
   # System-wide installation
   sudo cp -r ChHsichNerdFont/* /usr/share/fonts/TTF/
   sudo fc-cache -f -v
   
   # User installation
   mkdir -p ~/.local/share/fonts
   cp -r ChHsichNerdFont/* ~/.local/share/fonts/
   fc-cache -f -v
   ```

## Usage

After installation, you can use the font in your applications by selecting "ChHsich Nerd Font" from the font list.

### Font Variants

- `ChHsichNerdFont-Regular` - Regular weight
- `ChHsichNerdFont-Bold` - Bold weight
- `ChHsichNerdFont-Italic` - Italic style
- `ChHsichNerdFont-BoldItalic` - Bold italic style
- `ChHsichNerdFont-Light` - Light weight
- `ChHsichNerdFont-LightItalic` - Light italic style
- `ChHsichNerdFont-Medium` - Medium weight
- `ChHsichNerdFont-MediumItalic` - Medium italic style
- `ChHsichNerdFont-SemiBold` - Semi-bold weight
- `ChHsichNerdFont-SemiBoldItalic` - Semi-bold italic style
- `ChHsichNerdFont-ExtraBold` - Extra-bold weight
- `ChHsichNerdFont-ExtraBoldItalic` - Extra-bold italic style
- `ChHsichNerdFont-Thin` - Thin weight
- `ChHsichNerdFont-ThinItalic` - Thin italic style
- `ChHsichNerdFont-ExtraLight` - Extra-light weight
- `ChHsichNerdFont-ExtraLightItalic` - Extra-light italic style

## Package Information

- **Package Name**: `chhsich-nerd-font`
- **Version**: 1.0.0
- **Architecture**: any
- **License**: OFL (SIL Open Font License)
- **Dependencies**: fontconfig, xorg-fonts-encodings, xorg-font-util
- **Provides**: ttf-chhsich-nerd-font
- **Conflicts**: ttf-chhsich-nerd-font
- **Replaces**: ttf-chhsich-nerd-font

## Package Structure

```
chhsich-nerd-font/
├── PKGBUILD                    # Package build script
├── chhsich-nerd-font.install   # Post-install script
├── README.md                   # This file
└── .gitignore                 # Git ignore rules
```

## Build Information

The package is built using `makepkg` and includes:

- 16 TTF font files (288.60 MiB installed size)
- Font configuration files
- Automatic font cache update on install/upgrade/remove

## License

This font is licensed under the SIL Open Font License, Version 1.1.

## Credits

- **ComicShannsMono Nerd Font** - Copyright (c) 2018 Shannon Miwa, Copyright (c) 2023 Jesus Gonzalez
- **Maple Mono NF CN** - Copyright 2022 The Maple Mono Project Authors

## Links

- [GitHub Repository](https://github.com/ChHsiching/chhsich-nerd-font)
- [GitHub Releases](https://github.com/ChHsiching/chhsich-nerd-font/releases)
- [AUR Package](https://aur.archlinux.org/packages/chhsich-nerd-font)
- [Nerd Fonts](https://www.nerdfonts.com/)

## Development

This AUR package is maintained by ChHsiching. For issues or contributions, please visit the [GitHub repository](https://github.com/ChHsiching/chhsich-nerd-font). 