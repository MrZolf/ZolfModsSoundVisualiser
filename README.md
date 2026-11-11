# Zolf Mods Sound Visualiser

A [Sine](https://github.com/CosmoCreeper/Sine) mod for Zen Browser: a mute button and an animated sound visualiser for **Essentials** tiles. Pure CSS - no JavaScript, so it does not need "Allow installing JS from unofficial sources".

## Features

- Mute button on Essentials, anchored to the whole tile (works with and without *Big Essentials*): shown on hover and always while the tab is muted.
- Position: top right, top left, bottom right, bottom left, middle high, middle low.
- Style: dark or light. Size: small, medium or big.
- Sound visualiser while a tab is playing: **bars** or a flowing **wave**, small / medium / large, above or behind the favicon.
- Colors: monochrome light / dark, blue, green, orange, pink, purple, red, yellow or the Zen accent color.
- Visualiser set to *None*: no animation, the mute button stays visible while the tab is playing.
- Respects `prefers-reduced-motion`.

## Settings

The first entry of every dropdown is built into Zen/Sine and is the default choice of that setting.

| Setting | Options (default first) |
| --- | --- |
| Mute icon position | Top right, Top left, Bottom right, Bottom left, Middle high, Middle low |
| Mute icon style | Dark, Light |
| Mute icon size | Medium, Small, Big |
| Sound visualiser | Animated, None |
| Sound visualiser style | Bars, Wave |
| Visualiser color | Monochrome light, Blue, Green, Monochrome dark, Orange, Pink, Purple, Red, Yellow, Zen accent color |
| Visualiser size | Medium, Small, Large |
| Visualiser layer | Behind favicon, Above favicon |

## Installation

1. Zen: **Settings → Sine Mods** → install from GitHub.
2. Paste `MrZolf/ZolfModsSoundVisualiser`.
3. Restart Zen and open the mod's settings.

## Files

- `theme.json` - Sine metadata.
- `preferences.json` - the settings above.
- `chrome.css` - all styles.
# ZolfModsSoundVisualiser
