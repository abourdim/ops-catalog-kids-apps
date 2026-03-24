# Flag Match

**Name the country from its flag!**

A single-file HTML interactive flag matching game for kids. Flags are drawn programmatically on a canvas element using simple shapes — no images, no dependencies, fully offline.

## Features

- **40+ flags** drawn with canvas (fillRect, arc, moveTo/lineTo)
- **3 difficulty levels**: Easy (10 well-known flags), Medium (20), Hard (40+)
- **Multiple choice**: 4 options per question
- **Fun facts**: After a correct answer, shows capital, continent, and a fun fact
- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual**: EN / FR / AR with RTL support
- **Sound**: Web Audio API tones (correct, wrong, win) — toggle on/off
- **High score**: Persisted in localStorage (`wdiy-hs-flag-match`)
- **Keyboard shortcuts**: 1-4 for answers, Enter to start, Escape to close help
- **Sidebar help**: FAQ, How-To, Wiki tabs
- **Preferences persist**: Theme, language, sound mute saved to localStorage
- **Zero dependencies**: Single HTML file, works offline

## Flag Categories

| Category | Countries |
|----------|-----------|
| Tricolors | France, Italy, Germany, Belgium, Ireland, Nigeria, India, UAE, Russia, Mexico, Peru, Austria, Netherlands, Colombia |
| Bicolors / Circle | Japan, Bangladesh, Poland, Indonesia, Monaco |
| Crescent + Star | Turkey, Pakistan, Tunisia, Algeria, Malaysia, Libya |
| Cross flags | Switzerland, Finland, Sweden, Denmark, Norway, UK |
| Striped | USA, Thailand, Greece, Cuba |
| Other | Saudi Arabia, Morocco, Brazil, Canada, China, South Korea, Egypt, Spain, Argentina, South Africa, Vietnam, Philippines, Chile, Portugal |

## Tech

- Single `index.html` — zero external assets
- Canvas 2D API for all flag rendering
- Web Audio API for sound effects
- localStorage for preferences and high scores
- CSS custom properties for theming

## Keys

| Key | Action |
|-----|--------|
| `1`-`4` | Pick answer |
| `Enter` | Start / New Game |
| `Escape` | Close help sidebar |

---

Workshop-Diy — Flag Match v1.0
