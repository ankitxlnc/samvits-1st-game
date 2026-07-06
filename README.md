# 🛹 Stickman Skate Dash

Samvit's first game! An endless auto-runner where a stickman rides a skateboard,
dodging rocks and trees, ducking under branches, and grabbing coins — solo or
two-player. Built as a single self-contained `index.html` (HTML5 Canvas + JS,
no dependencies, no build step).

## ▶️ Play

- **Online:** enable GitHub Pages (Settings → Pages → Branch `main` / root), then play at
  `https://ankitxlnc.github.io/samvits-1st-game/`
- **Locally:** just open `index.html` in any browser, or serve the folder:
  ```bash
  python3 -m http.server 8000
  # then open http://localhost:8000
  ```

## 🎮 Controls

**Player 1** — `←` `→` move · `↑` / `Space` jump · `↓` duck
**Player 2** (2-player mode) — `A` `D` move · `W` jump · `S` duck

`P` pause · `M` mute · `Enter` / tap to start & restart

## ✨ Features

- **Endless auto-runner** — speed ramps up the farther you go
- **Obstacles** — 🪨 rocks & 🌳 trees to jump, low branches to duck under
- **🪙 Coin pickups** — grab coins in ground rows, jump arcs, and high floats
- **1 or 2 players** on the same screen, each with their own 3 lives & coins
  - 2-player winner is ranked by **distance survived** (coins break ties)
- **Three worlds** — 🏙️ City, 🌴 Jungle, 🏜️ Desert (parallax backgrounds)
- **Day ↔ night** cycle every minute — moving sun/moon, stars, lit city windows
- Smooth animated skater (running, jumping, ducking, leaning), particles,
  screen shake, WebAudio sound effects, high-score saving, and touch controls

Have fun! 🎉
