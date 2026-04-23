# 🌌 MoodScape — Emotion-to-Environment Generator

> *Your emotion, rendered as a living world.*

MoodScape is an interactive web application that translates the way you **feel** into a **real-time, animated visual environment** — complete with sky, terrain, weather, celestial bodies, fireflies, aurora, lightning storms, and more.

---

## 🚀 How It Works

1. Type how you feel in the text area (or pick a mood chip)
2. Adjust **Intensity** (1–10) to scale the effect
3. Toggle **Day / Night** for an alternate view
4. Click **Generate World** — and watch your world come alive

---

## ✨ Unique Element

> **Emotion-Driven Procedural World Generation**

This is the core innovation: **natural language mood parsing that drives a full procedural scene renderer**, all in-browser with no back-end.

- The app parses your free-form text to detect emotional tone using a keyword-scoring engine across **8 distinct mood profiles** (Calm, Joyful, Melancholic, Furious, Hopeful, Mystical, Nostalgic, Numb).
- Each mood maps to a unique combination of: sky gradient palette, celestial body (sun/moon color, size, glow), cloud density, rain, snow, lightning storms, firefly count, aurora borealis, terrain shape, tree color, and ambient label text.
- The **Intensity slider** scales all particle counts and storm frequency proportionally.
- Every scene uses **randomised procedural SVG terrain**, **randomly placed trees**, and **random particle physics** — no two generations are identical.

No other submitted project uses this combination of **NLP-style sentiment parsing + CSS procedural art generation + jQuery-driven live DOM orchestration** as its central mechanic.

---

## 🛠 Technologies Used

| Technology | Usage |
|------------|-------|
| **HTML5**  | Semantic structure, SVG terrain |
| **CSS3**   | Keyframe animations, CSS variables, backdrop-filter, gradient transitions |
| **JavaScript (ES6)** | Mood detection engine, world state machine, procedural generation |
| **jQuery 3.7.1** | DOM manipulation, event handling, particle injection, fade effects |

---

## 📁 Project Structure

```
MoodScape/
├── index.html   ← Single-file app (HTML + CSS + JS + jQuery)
└── README.md
```

---

## 🎭 Mood Profiles

| Mood | Sky | Weather | Special Effect |
|------|-----|---------|----------------|
| Calm | Deep navy | None | Fireflies |
| Joyful | Orange-gold sunset | Scattered clouds | Bright sun |
| Melancholic | Dark slate | Heavy rain | Dim moon |
| Furious | Blood red | Lightning storm | Red sun |
| Hopeful | Dawn blue | Light clouds | Fireflies |
| Mystical | Near-black | Light snow | Aurora borealis |
| Nostalgic | Amber dusk | None | Warm fireflies |
| Numb | Pure grey | Overcast | Dim moon |

---

## 📌 Setup

No build step needed. Open `index.html` in any modern browser.

```bash
git clone https://github.com/YOUR_USERNAME/moodscape.git
cd moodscape
open index.html
```

Requires internet for Google Fonts + jQuery CDN.

---

*Built with Claude (Anthropic) as an AI-assisted project — Web Development Mini Project 2026.*
