# Logic Gates — Workshop-Diy

> Learn how computers think

An interactive logic gates simulator for kids. Explore AND, OR, NOT, XOR, NAND, and NOR gates with visual wires, toggleable inputs, real-time output, truth tables, and quiz challenges.

## Features

- **Explore Mode**: Select any gate, toggle inputs A and B, see output update in real-time
- **Canvas Visualization**: Standard gate symbols drawn on canvas with colored wires (green = 1, gray = 0)
- **Truth Table**: Live truth table highlights the current input combination
- **Quiz Mode**: Challenges ask kids to identify which gate produces a given output
- **3 Difficulty Levels**:
  - Easy (8 Qs): AND, OR, NOT
  - Medium (12 Qs): + XOR
  - Hard (20 Qs): + NAND, NOR, value questions
- **20+ unique challenges** covering all 6 gates
- **8 CSS Themes**: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **High Score**: Persisted in localStorage (`wdiy-hs-logic-gates`)
- **Timer**: Tracks elapsed time during quiz
- **Sound Effects**: Web Audio API (correct, wrong, win sounds) — toggle on/off
- **Keyboard Shortcuts**: A/B to toggle inputs, 1-6 for quiz answers, Enter to start, Escape to close help
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Single HTML file**, zero dependencies, fully offline

## How to Run

Open `index.html` in any modern browser. No server or build step required.

## Keyboard Shortcuts

| Key     | Action                        |
|---------|-------------------------------|
| A       | Toggle input A (Explore mode) |
| B       | Toggle input B (Explore mode) |
| 1-6     | Pick answer (Quiz mode)       |
| Enter   | Start / New Game              |
| Escape  | Close help sidebar            |

## Tech

- Single-file HTML with inline CSS and JS
- Canvas 2D API for gate symbol rendering
- Web Audio API for sound effects
- localStorage for theme, sound, and high score persistence

## Credits

Workshop-Diy — Logic Gates v1.0
