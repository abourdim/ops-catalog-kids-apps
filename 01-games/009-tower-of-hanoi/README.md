# 🗼 Tower of Hanoi

**Move all discs. Never place big on small. Fewest moves wins.**

---

## بِسْمِ ٱللَّٰهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ

## 🎯 Purpose

A classic mathematical puzzle. Move a stack of discs from peg A to peg C, one at a time. You can never place a larger disc on a smaller one. The challenge: do it in the minimum number of moves.

## 📖 What You'll Learn

- Recursive thinking — the solution has a beautiful recursive structure
- Planning ahead — you must think several moves ahead
- Exponential growth — each extra disc doubles the minimum moves (2ⁿ−1)
- Problem decomposition — breaking a big problem into smaller sub-problems
- Optimization — trying to match the optimal solution

## 🎮 How to Play

1. Choose number of discs (3-7)
2. Press ▶ New Game
3. Click a peg to pick up its top disc (or press 1/2/3)
4. Click another peg to place the disc there
5. Rule: you cannot place a bigger disc on a smaller one!
6. Move all discs from peg A to peg C to win
7. Try to match the optimal move count

## 📊 Optimal Moves

| Discs | Minimum Moves |
|-------|--------------|
| 3 | 7 |
| 4 | 15 |
| 5 | 31 |
| 6 | 63 |
| 7 | 127 |

Formula: 2ⁿ − 1 (where n = number of discs)

## 💡 Tips

- Start with 3 discs to learn the pattern
- The key insight: to move n discs, first move n-1 to the middle peg, then move the biggest to the target, then move n-1 from middle to target
- The smallest disc always moves every other turn

## 🔗 Based On

**Tower of Hanoi** — invented by French mathematician Édouard Lucas in 1883. Also featured in GCompris.

## 📄 License

Workshop-DIY — [abourdim](https://github.com/abourdim)
