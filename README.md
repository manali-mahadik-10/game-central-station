# 🎮 Game Central Station OS
### *Wreck-It Ralph Interactive Arcade Management Simulator*

> **"I'm gonna wreck it!"** — and you're gonna fix it.

A browser-based interactive game simulator set in the world of **Wreck-It Ralph**. You play as the System Administrator of Game Central Station — the hub connecting all arcade games. Ralph has gone rogue and it's your job to repair the damage!

---

## 🕹️ How to Play

1. **Boot the OS** — Watch the system boot and detect Ralph
2. **Pick a Game** — Choose from Fix-It Felix Jr., Hero's Duty, or Sugar Rush  
3. **Select a Character** — Pick your repair technician (avoid Ralph!)
4. **Fix Glitches** — Type repair codes into the terminal and press ENTER
5. **Win!** — Fix all glitches and restart the game for maximum score

📖 **Full guide:** [How to Play](pages/how-to-play.html)

---

## ✨ Features

- 🖥️ **Authentic OS boot sequence** with animated progress bar
- 🎮 **3 full game worlds** — each with unique characters & glitches  
- ⌨️ **Terminal repair system** — type real codes to fix glitches
- 📊 **Live system monitor** — stability meter, score tracker, system log
- 🎨 **Full CRT retro aesthetic** — scanlines, glitch effects, neon glow
- 🏆 **Leaderboard** — save and compete on high scores
- 💥 **Ralph chaos system** — clicking Ralph destroys system integrity!
- 📖 **How to Play page** — beginner-friendly guide
- ℹ️ **About page** — full project breakdown

---

## 📁 Project Structure

```
game-central-station/
├── index.html              ← Main game (boot → play → victory)
├── css/
│   └── global.css          ← Shared styles across all pages
├── pages/
│   ├── how-to-play.html    ← Complete beginner guide
│   ├── leaderboard.html    ← Score rankings & achievements  
│   └── about.html          ← Project info & tech stack
└── vercel.json             ← Vercel deployment config
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Multi-page architecture, semantic structure |
| CSS3 | Animations, CSS variables, Grid, Flexbox, @keyframes |
| Vanilla JavaScript | Game logic, state management, DOM manipulation |
| Google Fonts | Press Start 2P, VT323, Orbitron |
| SVG | Inline pixel-art character illustrations |
| localStorage | Persistent leaderboard scores |
| Vercel | Deployment & hosting |

**Zero frameworks. Zero dependencies. Pure code.**

---

## 🚀 Deployment

Live on Vercel: `https://game-central-station.vercel.app`

### Run Locally
```bash
# Option 1: Just open the file
open index.html

# Option 2: Local server (Python)
python -m http.server 8000
# Visit: http://localhost:8000

# Option 3: Node.js
npx serve .
```

---

## 🎯 Scoring

| Action | Points |
|---|---|
| Fix CRITICAL glitch | +300 pts |
| Fix HIGH glitch | +200 pts |
| Fix MEDIUM glitch | +100 pts |
| Time bonus (under 10 min) | Up to +600 pts |
| Ralph button | -150 pts |
| Clicking Ralph | -15% stability |

---

*Inspired by Wreck-It Ralph (2012) — Disney Animation*  
*Built with ❤️ using pure HTML, CSS & JavaScript*