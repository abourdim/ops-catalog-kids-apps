# Circuit Builder

Interactive circuit building simulation for kids. Place batteries, bulbs, switches, resistors, and wires on a grid canvas to build working electrical circuits.

## Features

- **Canvas-based grid**: 8x6 grid where kids place components and draw wires
- **5 Components**: Battery, Wire, Light Bulb, Switch, Resistor — drawn as simple shapes
- **Circuit analysis**: BFS-based algorithm detects complete circuits; bulbs glow yellow when current flows
- **Switch toggle**: Click any switch to open/close it and see the circuit respond in real-time
- **12 Challenges** across 3 difficulty levels:
  - **Easy (3)**: Simple battery+wire+bulb circuits
  - **Medium (4)**: Add switches, resistors, series connections
  - **Hard (5)**: Parallel circuits, multi-branch designs, master challenge
- **Hint system**: Dashed overlay shows suggested component placement
- **Clear & Reset**: Clear the board or start a new game at any time
- **Visual feedback**: Working circuit = bulb glows yellow with glow effect; broken circuit = bulb stays dark

## Structure

Single HTML file, zero dependencies, fully offline.

- `index.html` — Complete application (HTML + CSS + JS)

## Template Compliance

Follows the Workshop-Diy app template:
- 8 CSS themes (Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand)
- Splash screen with Bismillah, Start Mission button, lang/theme switchers
- App structure: hdr-bism, hdr, ctrl, status, game-area, score-row, log-box, foot
- Sidebar help panel with FAQ, How-To, Wiki tabs
- JS functions: setLang, setTheme, snd (Web Audio), log, high score (localStorage)
- Back-link to catalog
- Keyboard shortcuts (1-6 for tools, T=test, H=hint, C=clear, N=next, Enter=start)
- Persisted preferences (theme, language, sound, high score)
- Trilingual: EN / FR / AR (with RTL support)

## Keys

- `HS_KEY`: `wdiy-hs-circuit-builder`
- **Footer**: Workshop-Diy — Circuit Builder v1.0
