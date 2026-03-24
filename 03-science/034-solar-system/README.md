# Solar System Explorer

Interactive Solar System Explorer for kids. Single-file HTML, zero dependencies, fully offline.

## Features

- **Explore Mode**: Animated canvas with the Sun and 8 planets orbiting at different speeds. Click any planet (or the Sun) to see an info card with name, distance, diameter, moons, temperature, and a fun fact.
- **Quiz Mode**: "Click on [planet]!" and superlative questions ("Which planet is the largest/hottest/coldest?"). Three difficulty levels.
- **8 CSS Themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand.
- **Trilingual**: English, French, Arabic (with RTL support).
- **Splash Screen**: Bismillah, Start Mission button, language/theme switchers.
- **High Score**: Persisted in localStorage (`wdiy-hs-solar-system-v2`).
- **Sound**: Web Audio API tones for correct/wrong/win. Toggle on/off. Preference persisted.
- **Keyboard Shortcuts**: Enter (start), E (explore mode), Q (quiz mode), 1-8 (select planet in quiz), Escape (close help).
- **Sidebar Help**: FAQ, How-To, Wiki tabs.
- **Responsive**: Canvas auto-resizes to container width.

## Planets

| Planet  | Color         | Moons | Fun Fact Highlight           |
|---------|---------------|-------|------------------------------|
| Mercury | Gray          | 0     | 59-Earth-day rotation        |
| Venus   | Yellow-orange | 0     | Spins backwards              |
| Earth   | Blue-green    | 1     | Only planet with known life  |
| Mars    | Red           | 2     | Tallest volcano (Olympus Mons) |
| Jupiter | Orange+stripes| 95    | Great Red Spot storm         |
| Saturn  | Gold+ring     | 146   | Ice and rock rings           |
| Uranus  | Light blue    | 28    | Rotates on its side          |
| Neptune | Dark blue     | 16    | Strongest winds              |

## Difficulty Levels

- **Easy**: 4 inner planets, 6 questions
- **Medium**: All 8 planets, 10 questions
- **Hard**: All 8 planets + superlative questions (largest, closest, hottest, coldest, most moons), 12 questions

## Tech

- Single HTML file, no external JS/CSS dependencies (only Google Fonts)
- Canvas animation via `requestAnimationFrame`
- Web Audio API for sound effects
- localStorage for preferences and high score persistence
- Works offline once loaded

## Credits

Workshop-Diy — Solar System v1.0
