# Chroma, a sleek theme for Nintendo Switch

Chroma is a NXTheme project that aims to (hopefully) bring sleek and responsive designs to your Switch interface. It's basically a set of themes that share similar UI design criteria. The intent here was to turn one year's worth of accumulated knowledge in Switch theming into full-fledged and coherent theme packs (notice the plural).

It comes in **5 layout variants for the home screen** (more specifically the games row), and it's pre-bundled with a few color schemes.

Contributors are always welcome, so feel free to fork this repository if you want to implement additional color schemes. Excluding bug reports, I won't be taking any requests.

## Features

**Important: set your console to dark mode before using Chroma** (System Settings > Themes > Basic Black)

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
- **Murasaki:** light purple with hints of beige and pale orange. Uses the default layout.
- **Neo Famicom:** gray tones and colored buttons inspired by the SNES console. Uses the 1:1 cards layout.
- (only home screen & player select) **Famicom:** wine red and beige colors, inspired by the Famicom console. Uses the default w/ sidebar layout.

## Theme editing

This repository contains the themes' source code as well as their assets. Before anything else, [check out the documentation](https://layoutdocs.themezer.net/) to learn more about editing layouts. Additionally, a wiki that explicits the specifics of those themes *might* be published at some point.

Now, please note that Chroma involves very intricate layouts as they massively rely on animations and convenient re-use of pre-existing UI elements (which is often the case with my NXTheme releases). You will most likely have a hard time to tweak those themes without breaking something. Also, most colors are dynamically handled (through animations) so making color changes isn't as straightforward as editing hex values within the JSON files. In fact, you will absolutely need Layout Editor for most of the UI.

**Credits would be greatly appreciated if you're planning to publicly share your edited theme.**

## Known issues

- In the sidebar layout, the games scrolling will behave weirdly if the sidebar is accessed through some particular ways. It doesn't affect the navigation that much and there's a chance you won't even notice. This issue actually arose in Unison R as well, and unfortunately I have no solution to prevent this behavior.

## Credits

- Atmosphere icon in Chroma Terra Edition by [dh park](https://thenounproject.com/icon/leaf-5958752/)
- Atmosphere icon in Chroma Aqua Edition by [Viktor Vorobyev](https://thenounproject.com/icon/water-drop-504908/)
- Atmosphere icon in all other variants by u/Quat0rz
- Switch controller SVG in Neo Famicom's lockscreen by [Chad Remsing](https://thenounproject.com/icon/switch-charging-controller-930118/)
- Special thanks to [LayoutDocs](https://layoutdocs.themezer.net/) contributors
