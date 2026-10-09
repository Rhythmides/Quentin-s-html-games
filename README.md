# Quentin's HTML Games

> A collection of 6 fully playable browser games & interactive sandboxes, all built via AI-Generated Content (AIGC) workflow. Each game ships as a single self-contained HTML file — zero dependencies, zero build step, runs directly in any modern browser.

---

## 🎮 Overview

This repository is a showcase of human-AI collaborative game creation. Quentin provided the core concepts, creative direction and design vision; DeepSeek and ChatGPT handled the full implementation — from game mechanics, rendering engine and UI to interactive logic and audio design.

The project explores a new paradigm of rapid game prototyping: turning creative ideas into polished, playable products through human-AI collaboration, dramatically lowering the barrier between concept and finished experience.

---

## ✨ Features

- 📦 **Single-file delivery** — every game is one standalone `.html` file
- 🚫 **Zero dependencies** — no frameworks, no libraries, no external assets
- 🌐 **Cross-platform** — runs on Chrome, Firefox, Edge, Safari; desktop & mobile
- 🎵 **Procedural audio** — all sound effects & BGM generated via Web Audio API
- 🎯 **Diverse genres** — simulation, strategy, action roguelite, sandbox, meta narrative, physics
- 💾 **Portable** — copy to USB, host on any server, send via email — works everywhere

---

## 📦 Games Included

| Game | File | Genre | Short Description |
|---|---|---|---|
| AAA OS | `computeraaa_2.3.html` | OS Simulation / Survival | A retro operating system simulator where you fight against endless pop-up ads before system load hits 100% and crashes |
| Chess War | `Chess War 2.3.html` | Strategy / Minigame Mashup | Turn-based strategy war game where every battle is resolved through a different classic minigame |
| Flatland | `flatland-4.1-dlc-2.1.html` | Action Roguelite | *Flatland* novel adaptation — evolve from triangle to circle, fight geometric bosses across a 2D world of shapes |
| Microcosm | `MICROCOSM-3.1.html` | Life Simulation / Sandbox | A realistic single-cell evolution sandbox with gene editing, metabolic networks and environmental ecology |
| SYE | `SYE-1.2.html` | Experimental Meta Narrative | When taking a vision test, I'm worried that my eyesight is getting worse and worse. Let's practice with this |
| Singularity | `SINGULARITY-2.1.html` | Physics Sandbox | Multi-force 2D physics playground with gravity, Coulomb force, springs, spin and magnetic interaction |

---

## 🕹️ How to Play

1. Download any `.html` file from this repository
2. Open it directly in your web browser (double-click or drag & drop)
3. That's it — no installation, no internet required after download

> 💡 Tip: For the best experience, use a Chromium-based browser with hardware acceleration enabled.

---

## 🛠️ Technical Details

All projects follow the same technical philosophy:
- **Pure vanilla web tech**: HTML5, CSS3 and vanilla JavaScript (ES6+)
- **Rendering**: Canvas 2D API for real-time graphics, inline SVG for vector UI
- **Audio**: fully procedural sound design via Web Audio API OscillatorNodes — no audio files
- **No external resources**: all icons, styles and logic are embedded in the single HTML file
- **Responsive design**: adaptive layouts with mobile breakpoints and touch input support
- **Version numbers** in filenames (e.g. `2.3`, `3.1`) represent AIGC iteration passes, each with gameplay refinements, UI improvements and bug fixes

---

## 📂 Repository Structure

```
Quentin-HTML-Games/
├── computeraaa_2.3.html       # AAA OS
├── Chess War 2.3.html          # Chess War
├── flatland-4.1-dlc-2.1.html   # Flatland
├── MICROCOSM-3.1.html          # Microcosm
├── SYE-1.2.html                # SYE
├── SINGULARITY-2.1.html        # Singularity
└── README.md
```

---

## 🧠 About the AIGC Workflow

This entire collection was created through an iterative human-AI collaboration pipeline:
1. **Concept phase**: Quentin defines the core idea, genre, mechanics and aesthetic direction
2. **Generation pass**: AI models produce full working implementation from the prompt
3. **Review & iteration**: Quentin tests, gives feedback and requests changes
4. **Refinement pass**: AI adjusts mechanics, fixes bugs, polishes UI and balances gameplay
5. **Final version**: numbered iteration is finalized and added to the collection

---

## 🤝 Credits

- **Concept, Design & Direction**: Quentin (Rhythmides)
- **AI Generation & Implementation**: DeepSeek, ChatGPT

---

## 📄 License

This project is released under the license specified in the repository. All games are provided as-is for educational and showcase purposes.
