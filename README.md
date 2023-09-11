# Chroma, a sleek theme for Nintendo Switch

Chroma is a NXTheme pack that aims to (hopefully) bring sleek and responsive designs to your Switch UI. You can choose among **5 layout variants for your games row**, and it's pre-bundled with a few color schemes.

The intent here was to turn one year's worth of accumulated knowledge in Switch theming into a full-fledged and coherent theme pack.

Contributors are always welcome, so feel free to fork this repository if you want to implement additional color schemes. Excluding bug reports, I won't be taking any requests.

## Features

**Layout variants**

- **Default:** rounded game cards. This layout leaves enough room to put a custom background image.
- **Default w/ sidebar for applet icons**
- **Compact:** rounded 1:1 icons. When a game is highlighted, its label overlaps the game's image.
- **1:1 regular:** big squared 1:1 icons. The focus animation when a game is highlighted is similar to what can be seen in SteamOS' Big Picture Mode.
- **1:1 cards:** squared game cards

**Color schemes**

- **B&W** (default)
- **Terra:** earthy colors inspired by Monokai. Uses the default layout.
- **Aqua:** aquamarine and deep blue colors. Uses the default w/ sidebar layout.
- **Famicom:** wine red and beige colors, inspired by the Famicom console. Uses the default w/ sidebar layout.
- **Modern Retro:** light gray, grayish black and multicolored stripes. Uses the 1:1 cards layout.

## Theme editing

This repository contains the theme's source code as well as its assets. Before anything else, [check out the documentation](https://layoutdocs.themezer.net/) to learn more about editing layouts. Additionally, a wiki that explicits the specifics of this theme *might* be published at some point.

Now, please note that Chroma involves very intricate layouts as they massively rely on animations and convenient re-use of pre-existing UI elements (which is often the case with my NXTheme releases). You will most likely have a hard time to tweak this theme without breaking something. Also, most colors are dynamically handled (through animations) so making color changes isn't as straightforward as editing hex values within the JSON files. In fact, you will absolutely need Layout Editor for most of the UI.

Credits would be greatly appreciated if you're planning to publicly share your edited theme.

## Known issues

- In the sidebar layout, the games scrolling will behave weirdly if the sidebar is accessed through some particular ways. It doesn't affect the navigation that much and there's a chance you won't even notice. This issue actually arose in Unison R as well, and unfortunately I have no solution to prevent this behavior.

## Credits

- Atmosphere icon in Chroma Terra Edition by [dh park](https://thenounproject.com/icon/leaf-5958752/)
- Atmosphere icon in Chroma Aqua Edition by [Viktor Vorobyev](https://thenounproject.com/icon/water-drop-504908/)
- Atmosphere icon in all other variants by u/Quat0rz
- Special thanks to [LayoutDocs](https://layoutdocs.themezer.net/) contributors
