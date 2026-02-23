# SlideFlow 🎯

> A beautiful, zero-dependency training presentation creator that runs entirely in your browser.

![SlideFlow](https://img.shields.io/badge/version-1.0.0-c8a96e?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-7c6fcd?style=flat-square)
![No Dependencies](https://img.shields.io/badge/dependencies-none-green?style=flat-square)

---

## ✨ Features

- **Upload `.md` files** or **paste text directly** — two input modes
- **Line-by-line reveal** — press `Enter` to unveil each bullet one at a time
- **Click to zoom** — click any visible line to spotlight it, dimming the rest
- **6 stunning themes** — Cosmos, Forest, Ember, Ocean, Dusk, Arctic
- **Auto-scaling** — font size adjusts automatically for dense slides
- **Smooth scrolling** — long slides scroll automatically as lines are revealed
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript
- **Works offline** — no server required, just open `index.html`

---

## 🚀 Quick Start

### Option 1 — Open directly
```bash
# Just open the file in any modern browser
open index.html
```

### Option 2 — Serve locally
```bash
# Using Node.js
npx serve .

# Using Python
python3 -m http.server 8080

# Using PHP
php -S localhost:8080
```

Then visit `http://localhost:8080`

### Option 3 — GitHub Pages (free hosting)
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app is live at `https://yourusername.github.io/slideflow`

---

## 📖 How to Use

### Creating Slides

**From a Markdown file:**
- Click the **Upload .md File** tab
- Drag & drop your `.md` file or click **Browse Files**
- Supports `.md`, `.markdown`, `.txt`

**By pasting text:**
- Click the **Paste Text** tab
- Paste or type your content using Markdown syntax

### Markdown Format

```markdown
# Slide Title
## Optional Subtitle

- Bullet point one
- **Bold text** supported
- *Italic text* supported
- `inline code` supported

---

# Next Slide
- Separate slides with --- on its own line
- Or just use # headings — auto-detected
```

### Keyboard Controls

| Key | Action |
|-----|--------|
| `Enter` | Reveal next line |
| `→` / `PageDown` | Next slide |
| `←` / `PageUp` | Previous slide |
| `Click` on line | Zoom / spotlight that line |
| `Esc` | Exit presentation |

### Themes

Choose from 6 atmospheric dark backgrounds:

| Theme | Palette |
|-------|---------|
| 🌌 Cosmos | Deep purple & blue |
| 🌲 Forest | Deep emerald green |
| 🔥 Ember | Dark crimson & orange |
| 🌊 Ocean | Navy & midnight blue |
| 🌅 Dusk | Purple & amber |
| 🧊 Arctic | Teal & ice blue |

---

## 🗂 Project Structure

```
slideflow/
├── index.html        # The entire app — single self-contained file
├── README.md         # This file
├── .gitignore        # Standard gitignore
├── package.json      # Project metadata
└── LICENSE           # MIT License
```

---

## 🛠 Tech Stack

- **HTML5** — semantic structure
- **CSS3** — animations, CSS variables, clamp(), custom scrollbar
- **Vanilla JavaScript** — no frameworks, no build step
- **Google Fonts** — Playfair Display, DM Sans, Cormorant Garamond (loaded from CDN)

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

MIT © 2024 — free to use, modify, and distribute.
