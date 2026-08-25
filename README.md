# Neon District — Director's Cut 9.5

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-9.5.0--SAFE-62e6ff)](https://github.com/Parvaz-Jamei/neon-district)
[![Single File](https://img.shields.io/badge/format-single--file%20HTML5-success)](index.html)
[![Offline](https://img.shields.io/badge/offline-ready-brightgreen)](#)
[![Made by](https://img.shields.io/badge/made%20by-Parvaz%20Jamei-ff66b3)](https://github.com/Parvaz-Jamei)

> **A neon-soaked living open-world city** built entirely in a single HTML file.  
> Simulation-grade driving • Style combos • Side hustles • Dynamic weather • Cinematic photo tools.

**Play instantly →** Open [`index.html`](index.html) in any modern browser.  
No install. No server. No dependencies.

---

## ✨ Highlights

- **100% Offline & Single-File** — One `.html` contains the entire game (engine, assets, systems).
- **Simulation Driving** — Slip physics, hydroplaning, visible vehicle damage, realistic handling.
- **Style System** — Near-misses, stunts, drift combos, clean escapes. Build meter & multipliers.
- **Living City** — Reactive crowds, living traffic, day/night cycle with solar lighting, dynamic weather.
- **Wanted Heat & Contracts** — 16 contracts + side hustles, tags, photo spots, micro-challenges.
- **Cinematic Tools** — Photo Mode with color grades + 4 skill arcades.
- **Adaptive Performance** — Soft particle trimming, FPS-aware caps, graceful degradation on low-end devices.
- **Controller Ready** — Keyboard, Touch, Gamepad support out of the box.

---

## 🎮 Controls

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

## 🚀 Quick Start

### Option 1 — Instant Play (Recommended)
1. Download or clone this repository
2. Double-click `index.html`
3. Play offline in Chrome, Edge, Firefox, or Safari

### Option 2 — Local Server (optional)
```bash
# Python
python -m http.server 8080

# or Node
npx serve .
```
Then open `http://localhost:8080`

### Option 3 — GitHub Pages
Once enabled, the game will be available at:  
`https://parvaz-jamei.github.io/neon-district/`

---

## 🛠 Tech Stack

- **Pure HTML5 + Canvas 2D**
- **Vanilla JavaScript** (no frameworks, no build step)
- **Zero external dependencies**
- **Adaptive rendering & particle system**
- **Spatial audio** (Web Audio API)
- **LocalStorage** save system
- **Responsive** (desktop + mobile)

This architecture makes the project:
- Extremely portable
- Easy to audit and contribute to
- Perfect for educational purposes and portfolios

---

## 📦 Project Structure

```
neon-district/
├── index.html          # The entire game (Director's Cut 9.5)
├── LICENSE             # MIT
├── README.md           # You are here
├── CONTRIBUTING.md     # How to contribute
├── CODE_OF_CONDUCT.md  # Community guidelines
└── .gitignore
```

---

## 🗺️ Roadmap & Contribution Ideas

We welcome contributors! Here are high-impact areas:

### High Priority
- [ ] More vehicle types & tuning
- [ ] Additional districts / landmarks
- [ ] Expanded contract system
- [ ] Better mobile UI polish
- [ ] Accessibility improvements (colorblind modes, reduced motion)

### Medium
- [ ] Save slots / cloud sync (optional)
- [ ] More photo mode filters
- [ ] Mini-games expansion
- [ ] Localization (Persian, etc.)
- [ ] Performance profiling tools

### Community
- [ ] Custom maps / district editor
- [ ] Replay / ghost system
- [ ] Multiplayer experiments (optional)

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 🧠 Debug & Development

Open browser console and type:

```js
window.__DC95()
```

Returns current version, style score, combo, FPS and particle count.

---

## 👤 Author

**Parvaz Jamei**  
Embedded Software Engineer | Industrial IoT & Edge AI  
📍 Iran · [GitHub](https://github.com/Parvaz-Jamei) · [Website](https://proio.ir)

This project started as a personal experiment in building a complete living open-world experience inside a single file.  
Director's Cut 9.5 is the polished, stable release after multiple iterations focused on performance, safety and feel.

---

## 📄 License

This project is released under the **MIT License**.  
You are free to use, modify, distribute and even commercialize it — just keep the copyright notice.

---

## 🌟 Support the Project

If you enjoy Neon District:

- ⭐ Star the repository
- 🐛 Open issues for bugs or ideas
- 🔀 Submit pull requests
- 📣 Share it with other developers

Thank you for playing and contributing!

---

*Neon District — Director's Cut 9.5 · Built with ❤️ by Parvaz Jamei*
