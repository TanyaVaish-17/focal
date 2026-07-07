# 🎯 Focal — Responsive Focus Timer

A distraction-free focus timer landing page, built with plain HTML5, CSS3, and vanilla JavaScript — no frameworks, no build step.

> **Project 1 — Responsive Frontend Interface**, DecodeLabs Full Stack Internship (Batch 2026)

---

## 📖 Overview

Focal is a single-page site where the hero itself is a working product: a live countdown ring that runs real focus/break cycles, not a screenshot standing in for one. The rest of the page — how it works, features, FAQ — supports that one job.

## ✨ Features

- ⏱️ **Live focus timer** — 15 / 25 / 50-minute sessions with an animated progress ring
- 🔁 **Automatic breaks** — switches to a 5-minute break after each session, 15 minutes after every fourth
- 📊 **Daily session count** — tracked locally per day, no account required
- 🌗 **Light / dark mode** — toggle in the header, remembered on return visits
- 📱 **Mobile-first responsive layout** — single column on phones, expands at tablet (768px) and desktop (1024px) breakpoints
- ♿ **Accessible by default** — semantic landmarks, visible focus states, `prefers-reduced-motion` support, skip link
- 🧩 **Accordion FAQ** and animated **hamburger nav** with no external libraries

## 🛠️ Tech Stack

| Layer      | Choice                          |
|------------|----------------------------------|
| Markup     | Semantic HTML5                  |
| Styling    | CSS3 — Grid, Flexbox, custom properties, `clamp()` |
| Behavior   | Vanilla JavaScript (ES6+)        |
| Fonts      | Montserrat (display) · Roboto (body) |
| Storage    | `localStorage` (theme + daily session count) |

## 📁 Folder Structure

```
focal/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── docs/
│   └── screenshots/        ← put your screenshots here (see below)
└── README.md
```

## 🚀 Installation & Running

No build tools or dependencies — it's static HTML/CSS/JS.

```bash
# 1. Clone or download the project
git clone <your-repo-url> focal
cd focal

# 2. Open it directly
open index.html          # macOS
# or double-click index.html in your file explorer

# 3. (Optional) serve it locally to avoid any browser file:// quirks
npx serve .
# or
python3 -m http.server 5500
```

## 🧭 Usage

1. Pick a session length (15 / 25 / 50 minutes).
2. Press **Start** — the ring drains as time passes.
3. When it hits zero, Focal automatically switches to a break countdown.
4. Toggle **light/dark mode** from the header; your choice is remembered.

## 📸 Screenshots

Capture these and drop them into `docs/screenshots/` using the exact filenames below — the README already points at these paths.

| Screenshot | Filename | What to capture |
|---|---|---|
| Hero / Timer (desktop) | `screenshots/hero-desktop.png` | Full hero section with the timer card, browser at ~1440px wide |

```text
docs/screenshots/hero-desktop.png
```

## 🔮 Future Improvements

- Custom session lengths via an input instead of fixed presets
- Optional sound/notification when a session ends
- Export session history beyond "today"

## 👩‍💻 Author

**Tanya** — Full Stack Development Intern, DecodeLabs (Batch 2026)
