# Chroma, a sleek B&W theme for Nintendo Switch

This repository contains the theme's source code as well as its assets. For modding purposes, a wiki that explicits the "inner workings" of this theme *might* be published at some point.

Please note that Chroma is a very intricate theme as it massively rely on animations and convenient re-use of pre-existing UI elements (which is often the case with my NXTheme releases). You will most likely have a hard time to tweak this theme without breaking something. Also, most colors are dynamically handled (through animations) so making color changes isn't as straightforward as editing hex values within the JSON files.

**Excluding bug reports, I won't be taking extra theme requests.** If you want to implement additional color schemes, feel free to fork this repository.

## Features

Chroma comes in **5 main variants**:

- **default:** rounded game cards. This layout leaves enough room to put a custom background image.
- **default w/ sidebar for applet icons**
- **compact:** rounded 1:1 icons. When a game is highlighted, its label overlaps the game's image.
- **1:1 regular:** big squared 1:1 icons. The focus animation when a game is highlighted is similar to what can be seen in SteamOS' Big Picture Mode.
- **1:1 cards:** squared game cards

Available color schemes:

- **B&W** (default)
- **Terra Edition:** earthy colors inspired by Monokai. Uses the default layout.
- **Thalassa Edition:** aquamarine and deep blue colors. Uses the default w/ sidebar layout.

## Known issues

- in the sidebar layout, the games scrolling will behave weirdly if the sidebar is accessed in very specific ways. It doesn't affect the navigation that much and there's a chance you won't even notice. This issue actually arose in Unison R as well, and unfortunately I have no solution to prevent this behavior.

## Credits

- Atmosphere icon in B&W variants of Chroma by u/Quat0rz
- Atmosphere icon in Chroma Terra Edition by [dh park](https://thenounproject.com/icon/leaf-5958752/)
- [LayoutDocs](https://layoutdocs.themezer.net/) contributors
