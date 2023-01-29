# G-dark Themes for Vscode

- [Getting started](#getting-started)
  - [Installation](#installation)
  - [Support](#support)
  - [Ohter Editors](#other-editors)
  - [Custom Setting](#custom-settings)

##
<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/preview.gif" style="margin:5px auto;border-radius:6px;box-shadow:0px 0px 35px -10px rgba(10,10,10,0.90)">

**Give it a try and if you like and can spare e few minutes of time, help spread the word, give a &star;
on github or leave a review if you have time, thank you and happy coding✌🏾**

## Getting started

### Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `g-dark`
3. Click **Install** to install it.
4. A drop down list will appear.
5. Select on of **g-dark theme** variants to preview
6. Press Enter to activate the theme

### Support

#### Languages

Optimized for ***PHP***, ***Laval***, ***Blade Template***, ***Jinja***, ***Python***,
***HTML***, ***CSS***, **JSON**, **Markdown**, ***JS (Vanilla)*** and ***Others Languages***.

#### Night Mode

All themes Work well with F.lux/Night Shift or other similar tools.

**Note:** *Some themes are work better in dark room or similar as well as some in bright room
or outside, I suggest you try every themes on different sets to find the one that work for you.*

*Tested on **macOS***

### Other Editors

- For [Atom](https://atom.io/users/stoneC0der)
- For [Nova](https://extensions.panic.com/extensions/stonec0der/stonec0der.GDarkTheme/)

### Custom Settings

#### Fonts

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

### Happy coding


All contribution are welcome

For any issues [Issues](https://github.com/stonec0der/g-dark-theme/issues).Thanks for your support!
