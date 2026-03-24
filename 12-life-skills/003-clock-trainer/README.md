# Clock Trainer

**Learn to tell time** — an interactive analog clock reading trainer for kids.

## Features

- **Quiz Mode**: An analog clock displays a random time; pick the correct digital time from 4 choices
- **Set Mode**: A digital time is shown; drag the hour and minute hands to match it
- Canvas-based analog clock with circle border, 12 hour numbers, hour/minute marks, hour hand (short/thick), minute hand (long/thin), center dot
- Three difficulty levels:
  - **Easy** (8 questions): hours only (:00)
  - **Medium** (12 questions): adds :15, :30, :45
  - **Hard** (15 questions): any 5-minute interval
- Daily activity hints after each correct answer (e.g., "3:00 — Time for an afternoon snack!")
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- Sound effects via Web Audio API (no external files)
- High score persistence via localStorage
- Keyboard shortcuts: 1-4 for answer buttons, Enter to start/confirm, Escape to close help
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Touch support for mobile drag in Set mode
- Single HTML file, zero dependencies, fully offline

## Usage

Open `index.html` in any modern browser. No server required.

## Storage Keys

| Key | Purpose |
|---|---|
| `wdiy-hs-clock-trainer` | High score (percentage) |
| `wdiy-theme` | Selected theme |
| `wdiy-mute` | Sound mute preference |

## Credits

Workshop-Diy — Clock Trainer v1.0
