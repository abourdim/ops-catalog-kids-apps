# Color Mixer

**Discover how colors combine** — an interactive color theory art tool for kids.

## Modes

### Free Mix
- Pick two colors from a palette of 8 (Red, Blue, Yellow, White, Black, Green, Orange, Purple)
- See the RGB-blended result in real-time as animated color circles
- Reset and experiment freely

### Quiz Mode
- A target color is shown; pick the two colors that combine to make it
- 3 difficulty levels:
  - **Easy** (8 questions): Primary to secondary color mixing
  - **Medium** (12 questions): Adds tertiary colors (red-orange, yellow-green, etc.)
  - **Hard** (15+ questions): Adds tints (+white) and shades (+black)
- Color theory fact shown after each correct answer
- High score tracking (persisted in localStorage)

## Challenges Include
- Secondary colors: Orange, Purple, Green
- Tertiary colors: Red-Orange, Yellow-Orange, Yellow-Green, Blue-Green, Blue-Purple, Red-Purple
- Tints: Pink, Light Blue, Light Yellow, Light Green, Light Purple, Light Orange
- Shades: Dark Red, Dark Blue, Dark Green, Dark Purple, Dark Orange, Gray

## Features
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with bismillah, Start Mission button, lang/theme switchers
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no external files)
- Keyboard shortcuts: 1-8 palette pick, Enter submit, R reset, F free mix, Q quiz mode, Esc close help
- High score persistence (localStorage key: `wdiy-hs-color-mixer`)
- Preferences persistence (theme, language, sound)
- Single HTML file, zero dependencies, fully offline

## Technical
- **File:** `index.html` (single file, self-contained)
- **Dependencies:** None (Google Fonts optional, degrades gracefully)
- **HS_KEY:** `wdiy-hs-color-mixer`
- **Footer:** Workshop-Diy — Color Mixer v1.0
