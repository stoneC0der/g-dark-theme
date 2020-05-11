# G-dark Theme for Vscode

---

## Atom Editor

G Dark themes for [Atom](https://atom.io/users/stoneC0der)

Optimized for **PHP**, **Laval**, **Blade Template**, **Jinja**, **Python**, **HTML**, **CSS**, **JSON**, **Markdown**, **JS (Vanilla)**, should be fine with **Others Languages**.

**ALTERNATIVE BACKGROUNDS FOR G SILVER, G DARK (OL => ONE LOVE) & G DARK BLUE HIGHT CONTRAST COMING SOON CURRENTLY TESTING**

Please open an [Issue](https://github.com/stonec0der/g-dark-theme/issues) if the themes don't display correctly for your languages Thanks.

Tested on **macOS**

- [Getting started](#getting-started)
  - [Installation](#installation)
  - [Custom Setting](#custom-settings)
  - [Activate theme](#activate-theme)

## Preview  

---

<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/testing/images/preview.gif" style="margin:5px auto;border-radius:6px;box-shadow:0px 0px 35px -10px rgba(10,10,10,0.90)">

### Getting started

You can install this theme by downloading or cloning this repo or from [vscode extensions website](https://marketplace.visualstudio.com/items?itemName=StoneC0der.g-dark-theme).

### Installation

Launch *Quick Open*:

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/>

<a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`

- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`

- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install g-dark theme
```

<!-- #### Packaged VSIX Extension

[Download the latest .vsix release](https://marketplace.visualstudio.com/_apis/public/gallery/publishers/Equinusocio/vsextensions/vsc-material-theme/latest/vspackage) file from the marketplace and install it from the command line

```shell
code --install-extension vsc-g-dark-theme-*.*.*.vsix
``` -->

or from within VS Code by launching *Quick Open* and running the *Install from VSIX...* command.

### Recommended scenarios to use this theme:

**Outdoor / Very bright room (daylight)**

- G Dark (Light)
- G Dark (Silver)
- G Dark (Purple)

**Indoor / Low light**

- G Dark (Night Shift)
- G Dark (One Love)
- G dark (One Love Dark Green) *coming soon*
- G Dark Blue (Light) *coming soon*
- Dark (Black Silver) *coming soon*

**Dark Room with Dimmed light**

- All The black themes including Hight Contrast one.

**Dark Room (only computer light)**

- All hight contrast themes
- Some of the dark themes might do

**Themes the I believe belong to every scenarios**

- G Dark (default)
- G Dark Blue (Light)

#### Custom Settings

To get the most out of this them please add the following configuration:

1. Download and install Haskling fonts
  [Hasklig](https://github.com/i-tu/Hasklig, "Hasklig") or [JetBreains Mono](https://www.jetbrains.com/lp/mono/)
2. Enable ligature in vscode setting or add to settings.json :

```json
  "editor.fontLigatures": true,
  "editor.fontWeight": "600",
  "editor.fontSize": 14.5,
  "window.zoomLevel": 1,
```
  
3. Install [Indent-Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow, "Indent-Rainbow")

- add this to settings.json:

  ```json
    "indentRainbow.colors": [
      "rgba(16,16,16,0.10)",
      "rgba(16,16,16,0.20)",
      "rgba(16,16,16,0.30)",
      "rgba(16,16,16,0.35)",
      "rgba(16,16,16,0.40)",
      "rgba(16,16,16,0.45)",
      "rgba(16,16,16,0.50)",
      "rgba(16,16,16,0.55)",
      "rgba(16,16,16,0.60)",
      "rgba(16,16,16,0.65)",
      ],
  ```

4 Add the following to setting.json

```json
    "editor.renderWhitespace": "selection",
```

5 Auto switch between dark and light theme (macOS only)

  Install [auto-darkmode](https://marketplace.visualstudio.com/items?itemName=LinusU.auto-dark-mode, "Auto Dark Mode")

- add the following to settings.json:

```json
    "autoDarkMode.darkTheme": "G Dark",
    "autoDarkMode.lightTheme": "G Light",
```

6 For colored brackets

```json
    "editor.fontWeight": "600",
    "bracketPairColorizer.forceUniqueOpeningColor":true,
    "bracketPairColorizer.forceIterationColorCycle":true,
    "bracketPairColorizer.colorMode":"Consecutive",
    "bracketPairColorizer.highlightActiveScope":true,
    "bracketPairColorizer.activeScopeCSS":[
        "borderStyle : solid",
        "borderWidth : 1px",
        "borderColor : {color}; opacity: 0.3",
        "backgroundColor : {color}"
    ],
    "editor.matchBrackets":"never",
    "bracketPairColorizer.showBracketsInGutter":true,
    "bracketPairColorizer.consecutivePairColors":[
        "()",
        "[]",
        "{}",
        ["<", "</"],
        ["<", "/>"],
        [
            "Gold",
            "Orchid",
            "LightSkyBlue",
            "#854442",
            "#08C08C"
        ],
        "Red"
    ],
```

### From Vscode

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `g-dark`
3. Click **Install** to install it.
4. A drop down list will appear.
5. Select on of **g-dark-default** theme variants to preview
6. Press Enter to activate the theme

## Activate theme

Launch *Quick Open*:

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl + Shift + P`
- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘ + Shift + P`
- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl + Shift + P`

Type `theme`, choose `Preferences: Color Theme`, and select one of the G-dark Theme variants from the list.

## Happy coding

If you do like this theme, give it a rating [G Dark-theme](https://marketplace.visualstudio.com/items?itemName=StoneC0der.g-dark-theme, "G Dark-theme")

All contribution are welcome

For any issues [Issues](https://github.com/stonec0der/g-dark-theme/issues).Thanks so much!
