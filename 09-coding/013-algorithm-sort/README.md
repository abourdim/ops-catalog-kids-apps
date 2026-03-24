# Sorting Visualizer

**See how algorithms sort data** — an interactive, canvas-based sorting algorithm visualizer for kids.

## Features

- **3 Algorithms:** Bubble Sort, Selection Sort, Insertion Sort
- **Watch Mode:** Pick an algorithm and speed, watch the sort animate step-by-step with color-coded bars (yellow = comparing, red = swapping, green = sorted)
- **Play Mode:** Perform the sort manually — click two bars to swap them, following hints that show which comparison to make next
- **Controls:** Algorithm selector, speed (slow/medium/fast), array size (5/10/15/20), Shuffle, Start, Step, Pause
- **Counters:** Step counter, comparison counter, swap counter
- **Algorithm Info:** Each algorithm has a brief explanation shown below the canvas
- **8 CSS Themes:** Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **Splash screen** with theme picker
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Keyboard shortcuts:** Enter (start), Space (pause), S (shuffle), N (step), H (help), Esc (close help)
- **Persisted preferences:** Theme, sound on/off, high score
- **High score** tracking via localStorage (`wdiy-hs-sort-visual`)
- **Sound effects** via Web Audio API (compare, swap, win sounds)
- **Single HTML file, zero dependencies, fully offline**

## Difficulty Guide

| Difficulty | Bars | Suggested Algorithm |
|------------|------|---------------------|
| Easy       | 5    | Bubble Sort         |
| Medium     | 10   | Selection Sort      |
| Hard       | 15+  | Insertion Sort      |

## Usage

Open `index.html` in any modern browser. No server or build step required.

## Tech

- Single-file HTML
- Canvas-based rendering
- Web Audio API for sound
- localStorage for preferences and high score
- Zero external dependencies (Google Fonts optional)

## Credits

Workshop-Diy — Sorting Visualizer v1.0
