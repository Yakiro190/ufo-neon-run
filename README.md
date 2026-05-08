# UFO Neon Run 👽

A fast arcade browser game where you pilot a UFO through a neon city, collect energy coins, and dodge urban obstacles.

## ✨ Highlights

- Smooth canvas gameplay (desktop + mobile)
- Neon-green visual style with glow effects
- Dynamic speed ramp and combo scoring
- Pickups: **Magnet** and **Shield**
- Built-in procedural synth soundtrack (toggle on/off)
- Local best-score saving via `localStorage`

## 🎮 Controls

### Desktop
- **Move:** `WASD` or Arrow Keys

### Mobile
- Drag the UFO directly on screen
- Or use on-screen directional buttons

## 🚀 Run locally

Because this is a single static file project, you can run it with any local static server:

```bash
# Option 1: Python
python3 -m http.server 8080

# Option 2: Node (serve)
npx serve .
```

Then open:

- `http://localhost:8080/index.html` (Python)
- or the URL returned by `serve`

## 📁 Project structure

```text
ufo-neon-run/
├─ index.html
├─ README.md
└─ .gitignore
```

## 🛠 Tech

- HTML5 Canvas
- Vanilla JavaScript
- CSS (single-file styling)

## 📄 License

MIT
