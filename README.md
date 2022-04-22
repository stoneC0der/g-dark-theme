# G-dark Themes for Vscode

---
<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/preview.gif" style="margin:5px auto;border-radius:6px;box-shadow:0px 0px 35px -10px rgba(10,10,10,0.90)">

A set of dual/unique background themes design to help protect you're eyes while optimizing readability
using common but beautiful color palettes uniquely.
**Give it a try and if you like and can spare e few minutes of time, help spread the word, give a &star;
on github or leave a review if you have time, thank you and happy coding✌🏾**

## Atom Text Editor

G Dark Themes for [Atom](https://atom.io/users/stoneC0der)

## Nova Text Editor

G Dark Themes for [Nova](https://extensions.panic.com/extensions/stonec0der/stonec0der.GDarkTheme/)

### Languages support

Optimized for ***PHP***, ***Laval***, ***Blade Template***, ***Jinja***, ***Python***,
***HTML***, ***CSS***, **JSON**, **Markdown**, ***JS (Vanilla)*** and ***Others Languages***.

Please open an [Issue](https://github.com/stonec0der/g-dark-theme/issues) if the themes
don't display correctly for your languages Thanks.

**Note:** *Some themes are work better in dark room or similar as well as some in bright room
or outside, I suggest you try every themes on different sets to find the one that work for you.*

#### Night Mode

All themes Work well with F.lux/Night Shift or other similar tools.

*Tested on **macOS***

- [Getting started](#getting-started)
  - [Installation](#installation)
  - [Custom Setting](#custom-settings)
  - [Activate theme](#activate-theme)

## Getting started

You can install this theme by downloading or cloning this repo or from [vscode extensions website](https://marketplace.visualstudio.com/items?itemName=StoneC0der.g-dark-theme).

### Installation

#### From Vscode

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `g-dark`
3. Click **Install** to install it.
4. A drop down list will appear.
5. Select on of **g-dark theme** variants to preview
6. Press Enter to activate the theme

Launch *Quick Open*:

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/><a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> **`Ctrl+P`**

- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> **`⌘+P`**

- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> **`Ctrl+P`**

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

### Custom Settings

To get the most out of this them please add the following configuration:

1 Download and install Haskling fonts
  [Hasklig](https://github.com/i-tu/Hasklig, "Hasklig") or [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

2 Enable ligature in vscode setting or add to settings.json :

```json
  "editor.fontLigatures": true,
  "editor.fontWeight": "600",
  "editor.fontSize": 14.5,
  "window.zoomLevel": 1,
```

3 Install [Indent-Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow, "Indent-Rainbow")

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

4 Add the following to setting.json to display white space indicator only on selection

```json
    "editor.renderWhitespace": "selection",
```

5 Auto switch between dark and light theme (macOS only)

  Install [auto-darkMode](https://marketplace.visualstudio.com/items?itemName=LinusU.auto-dark-mode,
  "Auto Dark Mode")

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

7 To use a unique color for vscode functions & methods Separator

```json
  "separators.methods.borderColor": "#64778b3a",  
  "separators.functions.borderColor": "#64778b3a",  
  "separators.constructors.borderColor": "#64778b3a",
  "separators.classes.borderColor": "#64778b3a",  
  "separators.enums.borderColor": "#64778b3a",  
  "separators.namespaces.borderColor": "#64778b3a",
```

### Activate theme

Launch *Quick Open*:

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl + Shift + P`
- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘ + Shift + P`
- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl + Shift + P`

Type `theme`, choose `Preferences: Color Theme`, and select one of the G-dark Theme variants from the list.

### Happy coding


All contribution are welcome

For any issues [Issues](https://github.com/stonec0der/g-dark-theme/issues).Thanks for your support!
