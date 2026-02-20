🐰 Bunny Home
A mobile-first puzzle game where you program a bunny's path to collect carrots and find its way home.
🎮 Play
Open index.html in any modern browser — no build step, no dependencies.
🕹️ How to Play

Pick a level from the snake-road map screen
Build a sequence of moves by tapping or dragging arrow tokens into the sequence bar
Hit Run to watch the bunny execute your program step by step
Win by collecting all 🥕 carrots and reaching the 🏠 house

🧩 Move Tokens
TokenAction⬆️ ⬇️ ⬅️ ➡️Move 1 step in that direction↗️ ↖️ ↘️ ↙️Diagonal jump (1 forward + 1 sideways)
⚠️ Rules

🧱 Hit a wall (move off the grid) → instant fail
⚫ Fall in a hole → instant fail
🥕 Must collect all carrots before entering the house
👣 Step limit — each level has a maximum number of tokens you can place

🗺️ Levels

30 levels arranged on a winding snake-road map
3×3 grid — Levels 1–2
5×5 grid — Levels 3–5
8×8 grid — Levels 6–30
Levels are procedurally generated with a seeded RNG — same level always produces the same board
Every level is validated by BFS to guarantee it's solvable within the step limit

⭐ Progression

Complete a level to unlock the next one
Earn ⭐⭐⭐ on every win
Progress is tracked on the map screen

🛠️ Tech

Pure HTML + CSS + JavaScript — single file, zero dependencies
BFS pathfinding for solvability validation
Seeded RNG for deterministic level generation
Drag & drop (mouse and touch) for sequence building

📁 Structure
BunnyHome/
└── index.html   # entire game in one file
└── README.md
License
MIT
