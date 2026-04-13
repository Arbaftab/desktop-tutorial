# ✍️ AirScript — Holographic Air Writing

> Write in the air using hand gestures tracked by your webcam. A futuristic, browser-based drawing experience powered by MediaPipe Hands — no installation required.

---

## 🚀 Demo

Open `airscript.html` in any modern browser, allow webcam access, and start drawing with your index finger in the air.

---

## ✨ Features

- **Real-time hand tracking** via MediaPipe Hands (runs entirely in the browser)
- **Gesture-based controls** — draw, undo, clear, and more — no keyboard or mouse needed
- **5 stroke styles** — Normal, Glow, Glitter, Rainbow, Dashed
- **10 color swatches** — Cyan, Pink, Lime, White, Gold, Red, Purple, Orange, Silver, and more
- **Adjustable stroke size** — slider (1–20px) with S / M / L / XL quick presets
- **Hologram effect** — triggered by holding a thumbs-up gesture
- **Animated particle background** for a futuristic aesthetic
- **Export options** — save drawing as PNG or record a 10-second WebM video clip
- **Collapsible side panel** — toggle with a pinch gesture to go full immersive

---

## 🖐️ Gesture Controls

| Gesture | Action |
|---|---|
| ☝️ Index finger extended | **Draw** |
| ✊ Index finger curled | **Pen Up** (lift pen) |
| 🖐️ Open palm | **Clear canvas** |
| ✌️ Peace sign | **Undo** last stroke |
| 🤏 Pinch | **Toggle UI panel** |
| 👍 Thumbs up (hold 0.5s) | **Activate Hologram** effect |

---

## 🎨 Stroke Styles

| Style | Effect |
|---|---|
| Normal | Clean solid line |
| Glow | Neon glow with blur |
| Glitter | Scattered sparkle particles |
| Rainbow | Animated hue-shifting color |
| Dashed | Dashed/dotted line |

---

## 📦 Tech Stack

| Technology | Purpose |
|---|---|
| [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) | Real-time hand landmark detection |
| HTML5 Canvas API | Multi-layer drawing (skeleton, strokes, particles) |
| MediaRecorder API | 10-second video clip recording |
| Google Fonts (Orbitron, Inter) | UI typography |
| Vanilla JavaScript | All app logic — zero frameworks |

> No npm, no build tools, no backend. Just one `.html` file.

---

## 🛠️ How to Run

1. **Download** `airscript.html`
2. **Open** it in a modern browser (Chrome or Edge recommended)
3. **Allow webcam access** when prompted
4. **Start drawing** in the air ✍️

> ⚠️ Requires a webcam and a browser that supports `getUserMedia`. Works best in good lighting with a plain background.

---

## 📁 Project Structure

```
airscript.html          ← Entire app in a single file
├── CSS                 ← Glassmorphism UI, animations, hologram overlay
├── HTML                ← Side panel, viewport, overlays
└── JavaScript
    ├── MediaPipe init  ← Hand tracking & gesture detection
    ├── Canvas layers   ← Skeleton, drawing, buffer, composite, particles
    ├── Gesture engine  ← draw / undo / clear / hologram / toggle UI
    ├── Stroke renderer ← Normal, Glow, Glitter, Rainbow, Dashed styles
    └── Export          ← PNG snapshot & WebM video recording
```

---

## 🗺️ Roadmap / Future Ideas

- [ ] Multi-hand support (two-handed drawing)
- [ ] Text recognition from air-drawn letters (OCR)
- [ ] More stroke styles (chalk, neon pulse, pixel)
- [ ] Custom color picker
- [ ] Save/load drawing sessions
- [ ] Mobile support via touch fallback

---

## 👤 Author

**Aftab** — BSc Data Science & Analytics, Elphinstone College, Mumbai

---

## 📄 License

This project is open source. Feel free to fork, modify, and build on it.

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
