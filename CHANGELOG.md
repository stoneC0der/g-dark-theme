# Change Log

**If you like this theme, please support it by giving it a star on [github](https://github.com/stonec0der/g-dark-theme) or leave a review on the [marketplace](https://marketplace.visualstudio.com/items?itemName=StoneC0der.vscode-g-dark-theme).**

**If you have any issue, please report them on the [issue page](https://github.com/stonec0der/g-dark-theme/issues)**

Thanks for the love, any suggestion is welcome

**Note:** *I don't use every features & parts of vscode UI that is customizable as such some themes may not work well hence the regulars updates if you have an issue please report it so I can improve the themes, thanks.*

## 4.4.0

[improvement] Input background

- oxford blue
- One Love (Black Pearl)

[fix] G-dark Minimal (midnight)

- fix unfocusedActiveForeground
  
[improvement] G-Dark Haiti (HC)

- replace purple #8400ff with #A342FF for better readability

[improvement] G-Dark Minimal-2 (Astronaut Blue)

- improvement editor.background and all properties previously using the color #21576d with #1e4e62
- improve sidebar.background and all properties previously using the color #214c5d with #1e4454

[improvement] G-Dark (H@cker)

- improve string, keyword, keyword control (bolded), and more

[improvement] Panel inactiveForground

- Haiti (HC), Jackson-Purple,Minimal (Midnight)

[improvement] G-Dark (Vulcan)

- improve menu foreground
- breadcrumbs foreground

[Improvement] Unify Comment foreground for all themes

- use tint of 40% of the editor.background (Dark themes)
- use shade of 40% of the editor.background (Light themes)

[improvement] G Dark-Shader (Mirage)

- improve editor.background from #1c0c2e to #190b29

[improvement] menubar button hover
  
- some themes

[improvement] remove or update deprecated properties

- All themes

[improvement] editorGutter (git decoration)

- use the same colors for all themes
- fine tune opacity for individual themes

[improvement] Icon.foreground

- use a specific theme color instead of default one

[improvement] G-Dark (Vulcan)

- fix quickInput foreground

## 4.3.3

- update extension buttons, icons, badge, starts, prerelease, sponsored to be uniform across themes
- improve extensions button display (HC Themes)

## 4.3.2

- Improve variables, keywords, string, operators & number display (Light themes)

## 4.3.1

- Fix editorStickyScroll.background & editorStickyScrollHover.background
- Reorganized some theme keys

## 4.3.0

- Improve badges visibility (added consistency & better readability *some themes had different colors for badges*)
- Improve editor.selection.background (visibility & transparency)
- Improve button & button.hover colors (visibility & transparency)
- Other minor Fixes

## 4.2.5

- Few UI change to G-dark (Alice Blue)
- Minor improve to most of the themes
- Add indentGuide & whitespaceRendering consistency across all themes *(Disable white spaceRendering from User settings if you don't need it)*
- Other minor Fixes

## 4.2.4

- Fixes

## 4.2.3

- Fixed debug output for light themes

## 4.2.2

- Minor improvements (Minimap, LineHighlight)
- Improved editor.background G Dark (Astro Blue, Default, Jackson Purple).

## 4.2.1

- Improved terminal completion hints
- Minor improvement of Astro secondary bg

## 4.2.0

### New

- Added a new dark theme - G Dark Minimal (Oxford Blue)
<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/g-dark-oxford-blue.png" style="margin:5px auto;border-radius:6px;box-shadow:0px 0px 35px -10px rgba(10,10,10,0.90)">
- Minor Improvements

## 4.1.1

- Reupload the theme after accidentally deleting it from the marketplace
**NOTE**
Long time user should delete the previous theme and install it again to receive new update, sorry about that.

## 4.1.0

- Improved terminal foregroundColors
- minor improvements in some themes
- Markup heading text now the same color as hash (#) sign
- New Color for markup.heading for all light themes

### Changes

- Changed G dark light themes (Glitter & Alice Blue) string color
- Change user defined Constant color in G Dark (Hint of red)
- JS variable constants are distinct from variables (uses same color as PHP users defined constants)
- Minor changes to G Dark One Love set of themes variable
- Other minor changes

## 4.0.4

- New added support for Sashes
- Minor changes to sidebar & activityBar
- Breadcrumbs (improved visual difference with editor background)
- Fixed list hover & activeSelection in some themes
- Fixed debugConsole output not visible for some themes
- Other minor improvements

## 4.0.3

### Fix

- Fixed editorMarkerNavigation in some theme with improvement for others
- Fixed activityBar badge background being different from badges background in some themes
- Overall improvement for Light Themes
- Others improvements in some themes (variables, lineNumbers, keywords, methods, inputs, Notification, DiffEditor & more)

## 4.0.2

- Further Debug status bar improvements

## 4.0.1

- removed test file from package

## 4.0.0

### New

- Added brand new themes with new syntax color
  - G Dark (Astro)
  - G Dark-Shader (H@ck3r)
  - G Dark-Shader (Haïti)
  - G Dark (Haïti)

- Added support for [Vscode Separators](https://github.com/alefragnani/vscode-separators) extension
  **Note: the initial support was using a default color for all themes for methods & functions, now that there are separators for classes, interfaces, enums, constructors & namespace I decided to use classes,methods,etc color scheme for the separators if you want single color for all add the settings below to your settings.json**

        "separators.methods.borderColor": "#64778b3a",  
        "separators.functions.borderColor": "#64778b3a",  
        "separators.constructors.borderColor": "#64778b3a",
        "separators.classes.borderColor": "#64778b3a",  
        "separators.enums.borderColor": "#64778b3a",  
        "separators.namespaces.borderColor": "#64778b3a",

### Changes

- **5 themes removed**
  - Blue Charcoal
  - Cool Black
  - Mirage (NS)
  - Dark Green Jungle

- **Redesigned themes**
  - G Dark (Mirage)
    - Syntax has been redesigned to a shade of pink & purple
    - Borders where changed too
  - G Dark (Midnight)
    - Syntax was redesigned
    - Renamed as G Dark-minimal-2

- **C**, **Javascript**, **JSON** & **Markdown** syntax for some elements has change
- Constants language, support constants now use the same color (except for PHP user define constant)
- The themes name as been changed to a less confusing naming convention
- Rename G Dark (OL) to G Dark (One Love)
- Active window title bar now has a different background color from the inactive one

### Improvements

- Fixes debug status bar in all themes (The color now match the button background color t be consistent with the theme)
- Improved widget Hover in some themes
- Improved peekview in some themes for consistency
- Other improvements & fixes

## 3.6.0

- Fixed comment foreground in G Dark (Valhalla)
- minors improvements

## 3.5.0

### Changes

- C related languages functions arguments are now consistent with other languages such PHP & JavaScript
- Added borderColor to inputs in some themes to improved visibility
- Cleaned/removed duplicates, unused properties
- Other improvements

**These theme will be removed in version 4.0.0 update:**

- **G Dark (Cool Black)**
- **G Dark (Blue Charcoal)**
- **G Dark (NS Mirage)**
- **G Dark (Dark Jungle Green)**

If you use any of the themes listed above and wish to keep using it, you can either extract the theme from the [G Dark Theme](https://github.com/stonec0der/g-dark-theme) & edit yourself then install or open an [issue](https://github.com/stonec0der/g-dark-theme/issues) I might upload another package with these on the marketplace but support and further improvements might be limited or nothing a all thank for the love.

## 3.4.2

- Minor fixes & improvements

**NOTE: *major update coming soon with lot of changes, new themes & improvements.***

## 3.4.1

- minor fixes

## 3.4.0

Improved peekView, editorSuggestionWidget, editorHoverWidget background, editor.hoverHighlight (All themes)
Improved listTree indent guide (G Dark Alice Blue & Glitter)
Improved selection.background for some themes
Other minor improvements

### New

- Redesigned icon
- Added border to findMatchHighlight, WordHighlight, WordHighlightStrong (All Themes)

## 3.3.1

### Changes

Change sidebarBackground to match activityBar background (G-Dark Mirage - High Contrast)
Change ActiveTab background to match editorBackground & removed white border (G-Dark Mirage - High Contrast)

## Improvements

- Fixed wordHighlight not working properly (G-Dark Jacksons-Purple)
- Improved selectionBackground (G-Dark Jackson-Purple & G-Dark Mirage - High Contrast)
- removed unused properties

## 3.3.0

### New

- Added two (2) new background shade for G Dark NS & G Dark OL

### Changes

- Switch activeTabBackground color with InactiveTabBackground for G Dark OL themes (The active tab now matches the editor background for G Dark OL (Dark Jungle Green)
- Minor improvements for G Dark NS (Vulcan)

## 3.2.0

- Minor improvements to variable, functions, string, tags and more (G Dark OL Dark Jungle, G Dark OL Black Perl)

### NEW

- Darken statusbar (G Dark OL Dark Jungle)
- Added identifier to themes with same syntax theme and different background-color

## 3.1.0

- Improved breadscrumb (G-dark Mirage)
- Improved editor background color & any ui using the same color (G-dark Dark Jungle Green)
- Improved variable, tag, punctuation, built-in function, string & attribute (G-dark Midnight)

## 3.0.1

- Fixed buttons & badges not displaying correctly for some themes
- Improve activityBarBadges for some themes

## 3.0.0

- Renamed all themes to match the editor background-color name (giving names to themes was becoming hard 😅)
- New light (G Dark Alice Blue) & dark theme (G Dark Valhalla)

## 2.3.1

- Fix icons foreground

## 2.3.0

- New Themes
- Improvements

## 2.2.2

- Added recommended scenarios/environments to use this theme

## 2.2.1

- Added back  a little bit of darkness to sidebar, tabs, panel and terminal, inputs,...
- Fixed terminal black forground

## 2.2.0

- Added shadow to all themes (mini-map & tabs)
- Change active tab for some themes to be the same as the editor background

- Improved background colors of some themes
- Improved indentGuide for some themes (only the active indent is now shown)

- Fixed peek view in some themes
- Fixed unexpected Active Tab top border (Removed)
- Fixed widget background for themes
- Fixed Tabs contrast border (Now has the same color as tab background)

**I Have made new themes with alternate background-color for:**

- *G Dark Blue (Contrast) => alternative (Light blue background)*
- *G Silver => alternative (Dark background Hight Contrast)*
- *G Dark (OL => One Love) => alternative (Green Like Background)*

**I'm Currently testing them, if you wish to try theme now, the pre-release version on will be uploaded to the testing branch before I push the the updated.**

**Current alternative are:**

- *G dark (Default) => G Dark (Purple)*
- *G Dark (Deep Dark Green) => G Dark (Night Shift)*

## 2.1.2

- Fix comments in dark themes

## 2.1.1

Changes

- User defined functions are now blue-like color
- Built-in functions indigo like color

Improvements

- improve font-color opacity to reduce eyestrain
- Improve editor background-color

## 2.1.0

New Themes

- G Dark (Purple)
- G Dark (Night Owl)

*Those are the last two (2) in the set, will keep improving from now on.*

## version 2.0.2

**Minor Improvements**

- Improved (UI & Syntax) - **All Themes**

**Minor Changes**

- Rename some themes
  - G Black renamed => G Dark (OL)
  - G Deep Dark Green => G Dark (Deep Green)
  - G Light (Solirize) => G Light

## Version 2.0.1

### G Black

**New**

- Support for foldBackground
- Border-color for findMatch & wordHighlight

**Minor Improvements**

- findMatch, wordHighlight, selectionHighlight & scrollBar

## G Dark

**New**

- Border-color for findMatch & wordHighlight

**Minor Improvements**

- selectionHighlight, hoverHighlight

## G Light

**New**

- FolgBackgroundColor
- Border-color for findMatch & wordHighlight, lineHighlight

**Minor improvements**

- Line Number

## G Silver

**New**

- Border-color for findMatch & wordHighlight

**Minor improvements**

- findMatch, findMatchHighlight

## G Dark Blue

**New**

- Border-color for findMatch, lineHighlight & wordHighlight
- foldBackground color

**Minor improvements**

- variable, functions, keywords, tags, tag attributes and many more

## G Deep Dark Green

**New**

- Border-color for wordHighlight
- foldBackground color

**Minor improvements**

- findMatch, Selection, wordHighlight bg & border
- change color of cursor to green

## Version 2.0

**New**

- Added ActivityBar ActiveBorder color
- Added three new theme

**New themes**

**G Dark Deep Dark Green** (Dark Room Theme)

<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/G-dark-deep-black.png" style="margin:5px auto">

**G Dark Black**

<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/G-dark-black.png" style="margin:5px auto">

**G Dark Silver** (Outdoor/Bright Room Theme)

<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/G-dark-silver.png" style="margin:5px auto">

**Fix**

- Fixed github tracking colors in all themes
- Selection background in inputs fields
- Terminal Colors
- Fixed Scrollbar in High Contrast theme (G Dark blue)
- Fixed breadscrumbs not display well

**CHANGES**

- Rename G Dark High Contrast to G Dark Blue
- Improve activity icons foreground to make theme less obstructives
- A lot of color improvement for visibility
- Change built-in functions color to differentiates from user define functions (G Dark blue)

## Version 1.2.0

- Fixed preview image

## Version 1.0.0

- Added Hight Contrast Theme

![H-php](https://user-images.githubusercontent.com/11365636/59718876-9a71fa80-920a-11e9-809c-22bc9c933bbe.png)

- Added Light Theme

![L-php](https://user-images.githubusercontent.com/11365636/59718896-a52c8f80-920a-11e9-9928-796bcb424754.png)

- Variable and users defined functions are now bold in the default theme as well as the Hight contrast version.

## Version 1.1.0

### G Dark

**Changes**

- Explorer Headers title,Terminal,debug consol,etc now has a light top border

**Changes**
<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/html.blade.png" style="box-shadow:0px 1px 45px -10px rgba(0,0,0,0.65);border-radius:5px;margin:25px auto">
<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/blade%20d.png" style="box-shadow:0px 1px 45px -10px rgba(0,0,0,0.65);border-radius:5px;margin:25px auto">

**Most notable changes are:**

- editor forground
- editor line number
- activity bar icons color
- editor Indent Guide
- git decoration
- setting inputs
- Move from light grey to light blue for icons,borders,explorer forground.
- Scrollbar is now transparent (opacity 0,2), hover on it and click to reveal (This is because i mostly don't use it) you can change the value with :
  "scrollbarSlider.background": "" in your editor settings.json

### G High Contrast

<img src="https://user-images.githubusercontent.com/11365636/59718885-9e058180-920a-11e9-866c-55cdd659f76c.png" style="box-shadow:0px 1px 45px -10px rgba(0,0,0,0.65);border-radius:5px;margin:25px auto">
<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/blade%20hc.png" style="box-shadow:0px 1px 45px -10px rgba(0,0,0,0.65);border-radius:5px;margin:25px auto">

**Most notable changes are:**

- breadcrumb
- setting
- peekview
- panelscrollabr
- sidebar
- tabs
- status bar
- editor gutter
- editor background

### G Light

**Fix**

- Fixed color theme in Markdown Files. All the content is now readable

<img src="https://raw.githubusercontent.com/stoneC0der/g-dark-theme/master/images/md%20l.png" style="box-shadow:0px 1px 45px -10px rgba(0,0,0,0.65);border-radius:5px;margin:25px auto">

## Version 0.0.7

- Minor changes

## Version 0.0.6

- Clean all unnecessary files

## Version 0.0.5

- Remove ligth theme (Will add as soon as fixed)

- Initial release
