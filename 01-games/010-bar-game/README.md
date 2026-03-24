# 🎯 Bar Game (Nim)

**Take 1, 2, or 3 bars. The one who takes the last bar loses!**

---

## بِسْمِ ٱللَّٰهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ

## 🎯 Purpose

A mathematical strategy game based on Nim. Take turns removing 1 to 3 bars. The player forced to take the last bar loses. Simple rules, but winning requires discovering the mathematical pattern.

## 📖 What You'll Learn

- Mathematical strategy — the winning pattern uses modular arithmetic
- Backward reasoning — working from the end to find the winning strategy
- Pattern recognition — spotting the repeating structure in the game
- Game theory — some positions are winning, some are losing, regardless of opponent skill

## 🎮 How to Play

1. Choose total bars (10, 15, or 21)
2. Choose max per turn (1-3 or 1-4)
3. Choose mode: vs Tux or 2 Players
4. Press ▶ New Game
5. Click a number button (or press 1-3) to take that many bars
6. Tux takes his turn (or Player 2 goes)
7. The player who takes the LAST bar loses!

## 🧠 The Secret Strategy

The winning pattern for "take 1-3, last bar loses":
- Leave your opponent with 1, 5, 9, 13, 17... bars (pattern: 4n+1)
- Always take enough to leave a multiple of 4, plus 1
- If there are 15 bars: take 2 (leave 13) → take enough to leave 9 → 5 → 1 → opponent is forced to take the last!

## 📊 Variants

| Total Bars | Max Take | Losing Positions |
|-----------|----------|-----------------|
| 15 | 1-3 | 1, 5, 9, 13 |
| 21 | 1-3 | 1, 5, 9, 13, 17, 21 |
| 15 | 1-4 | 1, 6, 11 |

## 🔗 Based On

**GCompris Bar Game** — based on the mathematical game of Nim, studied since at least the 17th century. Fully solved by Charles Bouton in 1901.

## 📄 License

Workshop-DIY — [abourdim](https://github.com/abourdim)
