<p align="center">
  <img alt="Gorgeus Logo" src="https://raw.githubusercontent.com/code-n-cool/Gorgeus-vscode/master/images/logo.png" width="100" />
</p>
<h1 align="center">
  Gorgeus Theme for VS Code
</h1>
<p align="center">
  A minimal, dark blue theme for <a href="https://Gorgeus-theme.netlify.com/">VS Code, Sublime Text, Atom, and more</a>.
</p>
<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=jamesramos.Gorgeus-vscode">
    <img alt="Version" src="https://img.shields.io/visual-studio-marketplace/v/jamesramos.Gorgeus-vscode?color=brightgreen" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=jamesramos.Gorgeus-vscode">
    <img alt="Downloads" src="https://img.shields.io/visual-studio-marketplace/d/jamesramos.Gorgeus-vscode" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=jamesramos.Gorgeus-vscode">
    <img alt="Installs" src="https://img.shields.io/visual-studio-marketplace/i/jamesramos.Gorgeus-vscode" />
  </a>
</p>

![demo](https://raw.githubusercontent.com/code-n-cool/Gorgeus-vscode/master/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Gorgeus`
3. Click **Install** to install it
4. Click **Reload** to reload the editor
5. Code > Preferences > Color Theme > **Gorgeus**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/code-n-cool/Gorgeus-vscode/blob/master/vsc-extension-quickstart.md)

## Icon Theme

The file icon theme seen in the screenshot above is [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with these settings:

```json
  "material-icon-theme.folders.color": "#8695b7",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
```

## Color Reference

### Syntax Colors

|                               Color                                | Usage                                           |
| :----------------------------------------------------------------: | ----------------------------------------------- |
| ![#c3a6ff](https://via.placeholder.com/10/c3a6ff.png?text=+) `#c3a6ff` | Keywords, constants, template literals          |
| ![#ffd580](https://via.placeholder.com/10/ffd580.png?text=+) `#ffd580` | Functions, classes, object literal keys         |
| ![#ffae57](https://via.placeholder.com/10/ffae57.png?text=+) `#ffae57` | Constants, operators                            |
| ![#bae67e](https://via.placeholder.com/10/bae67e.png?text=+) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6.png?text=+) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://via.placeholder.com/10/a2aabc.png?text=+) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                               Color                                | Usage                                      |
| :----------------------------------------------------------------: | ------------------------------------------ |
| ![#171c28](https://via.placeholder.com/10/171c28.png?text=+) `#171c28` | Workbench background                       |
| ![#1d2433](https://via.placeholder.com/10/1d2433.png?text=+) `#1d2433` | Editor background                          |
| ![#2f3b54](https://via.placeholder.com/10/2f3b54.png?text=+) `#2f3b54` | Highlight, widgets, panels                 |
| ![#6679a4](https://via.placeholder.com/10/6679a4.png?text=+) `#6679a4` | Dividers, subtle UI elements               |
| ![#8695b7](https://via.placeholder.com/10/8695b7.png?text=+) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://via.placeholder.com/10/d7dce2.png?text=+) `#d7dce2` | Active text, anything that should be white |
| ![#ffcc66](https://via.placeholder.com/10/ffcc66.png?text=+) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#bae67e](https://via.placeholder.com/10/bae67e.png?text=+) `#bae67e` | Addition highlights                        |
| ![#ef6b73](https://via.placeholder.com/10/ef6b73.png?text=+) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6.png?text=+) `#5ccfe6` | Modified highlights                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Syntax & Workbench colors based on [Ayu Mirage Theme](https://github.com/teabyii/vscode-ayu)

```bash
vsce publish patch/minor/major
```

## Shameless Plug

Gorgeus is also available for [Sublime Text, Atom, iTerm, and more!](https://Gorgeus-theme.netlify.com/).
