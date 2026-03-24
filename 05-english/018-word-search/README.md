# Word Search — Workshop-Diy

Interactive word search puzzle generator for kids. Find hidden words in a grid of letters.

## Features

- **Procedural generation**: Every puzzle is unique — words placed randomly in the grid
- **8 word categories**: Animals, Colors, Fruits, School, Nature, Space, Body, Sports (8-12 words each)
- **3 difficulty levels**:
  - Easy: 8x8 grid, horizontal only, 6 words
  - Medium: 10x10 grid, horizontal + vertical, 8 words
  - Hard: 12x12 grid, all directions (horizontal, vertical, diagonal), 10 words
- **Click & drag selection**: Click first letter, drag to last letter to select a word
- **Visual feedback**: Selected letters highlight during drag; found words turn green permanently
- **Word list**: Found words get crossed off with a checkmark
- **Timer**: Tracks how fast you complete the puzzle
- **High score**: Best time saved to localStorage
- **8 CSS themes**: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 languages**: English, French, Arabic (with RTL support)
- **Splash screen**: Bismillah + Start Mission entry
- **Sidebar help**: FAQ, How-To, Wiki tabs
- **Sound effects**: Web Audio API (found, error, win sounds)
- **Keyboard shortcuts**: Enter (start), N (new puzzle), Escape (close help)
- **Persisted preferences**: Theme, language, sound, high score saved in localStorage
- **Single HTML file, zero dependencies, fully offline**

## How to Play

1. Choose a word category and difficulty level
2. Click **New Puzzle** to generate a grid
3. Find words from the list hidden in the grid
4. Click the first letter of a word, drag to the last letter, then release
5. Found words highlight green and get crossed off the list
6. Find all words to complete the puzzle

## Technical

- Single-file HTML (~15KB)
- No external dependencies (fonts loaded from Google Fonts but not required)
- Web Audio API for sound (no audio files)
- localStorage for preferences and high scores
- Touch and pointer event support for mobile
- `HS_KEY`: `wdiy-hs-word-search`

## File

```
018-word-search/
  index.html   — Complete game (single file)
  README.md    — This file
```
