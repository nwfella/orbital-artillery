# Orbital Artillery 🔫🪐

A 2-player hot-seat artillery duel set in orbit. Two players control proton cannons mounted on planets orbiting a sun — adjust angle and power, fire under the sun's gravity, and score direct hits on your opponent.

**Play it live:** https://nwfella.github.io/orbital-artillery

---

## How to Play

Two planets orbit a central sun. Each turn, a player aims their cannon and fires a projectile that curves under the sun's gravitational pull. Hit the enemy planet to score.

| Control | Action |
|---------|--------|
| `A` / `D` or `←` / `→` | Adjust cannon angle |
| `W` / `S` or `↑` / `↓` | Adjust power (10–100) |
| `Space` | Fire proton cannon |

- **Player 1** (Cyan) — faster inner orbit
- **Player 2** (Magenta) — slower outer orbit
- **Sun** pulls all projectiles with realistic inverse-square gravity
- **First to hit wins the round** — score displayed top-right

---

## Features

- 🌟 Orbital gravity mechanics — projectiles curve around the sun
- 🪐 Glowing planets with orbit trails and atmospheric effects
- ☀️ Radiant sun with solar flares and bloom
- 💫 Twinkling starfield background
- 🎯 Real-time angle/power HUD
- 🔄 Automatic turn switching after misses
- 🏆 Persistent score tracking across rounds

---

## MIT License

```
MIT License

Copyright (c) 2026 nwfella

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Development

Orbital Artillery is a single-file HTML5 Canvas game with zero dependencies. Open `index.html` in any modern browser to run it locally.

```
orbital-artillery/
├── index.html          # The complete game
└── README.md           # This file
```

---

*Built with vanilla JS, canvas 2D, and questionable orbital physics.*
