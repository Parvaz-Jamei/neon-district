# Neon District — Director's Cut 9.5

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-9.5.0--SAFE-62e6ff)](https://github.com/Parvaz-Jamei/neon-district)
[![Single File](https://img.shields.io/badge/format-single--file%20HTML5-success)](#)
[![Offline](https://img.shields.io/badge/offline-ready-brightgreen)](#)
[![Made by](https://img.shields.io/badge/made%20by-Parvaz%20Jamei-ff66b3)](https://github.com/Parvaz-Jamei)

> **A complete neon-soaked open-world experience** inside a single HTML file.  
> Simulation driving • Style combos • Living city • Dynamic weather • Cinematic tools.

**No install. No server. No dependencies.**  
Just open the file and play.

---

## Highlights

- **100% Offline & Single-File** — The entire game (engine, systems, UI) lives in one `.html` file.
- **Simulation-Grade Driving** — Slip physics, hydroplaning, visible damage, realistic handling.
- **Style System** — Near-misses, stunts, drift combos and clean escapes with meter & multipliers.
- **Living City** — Reactive crowds, traffic, solar day/night cycle and dynamic weather.
- **Contracts & Side Hustles** — 16 contracts, tags, photo spots and micro-challenges.
- **Cinematic Tools** — Photo Mode with color grades + 4 skill arcades.
- **Adaptive Performance** — FPS-aware particle & glow budgets. Stays smooth on low-end devices.
- **Full Input Support** — Keyboard, touch and gamepad ready.

---

## Controls

| Input | Action |
|-------|--------|
| **WASD / Arrows / Joystick** | Move & Drive |
| **Shift** | Sprint / Boost |
| **E** | Enter / Exit vehicle |
| **F** | Interact |
| **Click / Space** | Attack |
| **Q** | Manual weapon wheel |
| **R** | Reload |
| **Ctrl / X** | Brake |
| **P** | Pause |
| **Tap Minimap** | Open full city map |

---

## Quick Start

### 1. Play Offline (Recommended)
1. Download or clone this repository
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari)
3. Play immediately — fully offline

### 2. Local Server (optional)
```bash
# Python
python -m http.server 8080

# or Node
npx serve .
```
Then open `http://localhost:8080`

### 3. GitHub Pages
Enable Pages in repository **Settings → Pages** (Source: `main` branch).  
The game will be available at:  
**https://parvaz-jamei.github.io/neon-district/**

---

## Tech Stack

- Pure **HTML5 + Canvas 2D**
- **Vanilla JavaScript** — zero frameworks, zero build step
- **Zero external dependencies**
- Adaptive rendering & particle system
- Spatial audio via Web Audio API
- LocalStorage save system
- Fully responsive (desktop + mobile)

This architecture makes the project extremely portable, easy to audit, and ideal for portfolios and learning.

---

## Project Structure

```
neon-district/
├── index.html              # The complete game (Director's Cut 9.5)
├── LICENSE                 # MIT
├── README.md               # This file
├── CONTRIBUTING.md         # How to contribute
├── CODE_OF_CONDUCT.md      # Community guidelines
├── SECURITY.md             # Security policy
├── package.json            # Project metadata
├── RELEASE_NOTES.txt       # Detailed release notes
└── .gitignore
```

---

## Roadmap & Contribution Ideas

Contributions are very welcome. High-impact areas:

**High Priority**
- More vehicle types and tuning
- Additional districts / landmarks
- Expanded contract and side-hustle system
- Mobile UI polish
- Accessibility (colorblind modes, reduced motion)

**Medium**
- Extra Photo Mode filters
- Mini-games expansion
- Localization (including Persian)
- Performance profiling helpers

**Community Ideas**
- District / map editor
- Replay & ghost system
- Experimental multiplayer

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## Debug Tools

Open the browser console and run:

```js
window.__DC95()
```

Returns: version, current style score, combo, FPS and active particle count.

---

## Author

**Parvaz Jamei**  
Embedded Software Engineer · Industrial IoT & Edge AI  

📍 Iran · [GitHub](https://github.com/Parvaz-Jamei) · [Website](https://proio.ir)

Neon District began as a personal challenge: how complete can a living open-world experience be while staying inside a single file?  
Director’s Cut 9.5 is the stable, performance-focused release after multiple careful iterations.

---

## License

Released under the **MIT License**.  
You are free to use, modify, distribute and commercialize the project — just keep the copyright notice.

---

## Support the Project

If you enjoy Neon District:

- ⭐ Star the repository
- 🐛 Open issues for bugs or ideas
- 🔀 Submit pull requests
- 📣 Share it with other developers

Thank you for playing and contributing!

---

*Neon District — Director’s Cut 9.5 · Built with care by Parvaz Jamei*
