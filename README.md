# 🐰 Bunny Home

A mobile-first puzzle game where you program a bunny's path to collect carrots and find its way home.

## 🎮 Play

Open `index.html` in any modern browser — no build step, no dependencies.

## 🕹️ How to Play

1. Pick a level from the snake-road map screen
2. Build a sequence of moves by tapping or dragging arrow tokens into the sequence bar
3. Hit **Run** to watch the bunny execute your program step by step
4. Win by collecting all 🥕 carrots and reaching the 🏠 house

## 🧩 Move Tokens

| Token | Action |
|-------|--------|
| ⬆️ ⬇️ ⬅️ ➡️ | Move 1 step in that direction |
| ↗️ ↖️ ↘️ ↙️ | Diagonal jump (1 forward + 1 sideways) |

## ⚠️ Rules

- 🧱 Hit a wall (move off the grid) → instant fail
- ⚫ Fall in a hole → instant fail
- 🥕 Must collect all carrots before entering the house
- 👣 Step limit — each level has a maximum number of tokens you can place

## 🗺️ Levels

- Starts with **30 levels** on a winding snake-road map
- Beat the last level to **unlock 30 more** — repeats indefinitely
- **Levels 1–2** — 3×3 grid
- **Levels 3–5** — 5×5 grid
- **Levels 6+** — 8×8 grid with increasing carrots and holes
- Levels are procedurally generated with a seeded RNG — same level always produces the same board
- Every level is validated by BFS to guarantee it's solvable within the step limit

## ⭐ Progression

- Complete a level to unlock the next one
- Earn ⭐⭐⭐ on every win
- Finish the last level to expand the map with 30 new challenges
- Progress is tracked on the map screen

## 🛠️ Tech

- Pure HTML + CSS + JavaScript — single file, zero dependencies
- BFS pathfinding for solvability validation
- Seeded RNG for deterministic level generation
- Drag & drop (mouse and touch) for sequence building
- Dynamic level expansion — no hard cap on total levels

## 📁 Structure

```
BunnyHome/
├── index.html   # entire game in one file
└── README.md
```

## License

MIT
