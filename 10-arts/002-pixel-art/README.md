# Pixel Art — Workshop-Diy

Canvas-based pixel art drawing tool for kids. Single HTML file, zero dependencies, fully offline.

## Features

- **Grid sizes**: Small (8x8), Medium (16x16), Large (32x32)
- **16-color palette**: Black, White, Red, Blue, Green, Yellow, Orange, Purple, Pink, Brown, Gray, Cyan, Lime, Navy, Maroon, Teal
- **Tools**: Paint (click/drag), Flood Fill, Eraser, Clear All
- **Templates**: Star, Heart, Smiley, House, Tree, Flower, Cat, Rocket — light gray outlines on the grid
- **Grid lines toggle**
- **Touch support**: tap and drag to paint on mobile/tablet
- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages**: English, French, Arabic (RTL)
- **Splash screen** with bismillah, Start Mission button, lang/theme switchers
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Sound effects** via Web Audio API (paint, fill, erase, clear)
- **Persistent preferences**: theme, language, sound, high score (pixels painted record)
- **Keyboard shortcuts**: P (paint), F (fill), E (erase), G (grid toggle), Escape (close help)

## Structure

```
002-pixel-art/
├── index.html   # Single-file app (HTML + CSS + JS)
└── README.md
```

## Usage

Open `index.html` in any modern browser. No server required.

## Storage Key

- `wdiy-hs-pixel-art` — pixels painted high score
- `wdiy-lang` — language preference
- `wdiy-theme` — theme preference
- `wdiy-mute` — sound preference

## Version

v1.0 — Workshop-Diy — Pixel Art
