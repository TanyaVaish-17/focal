# 🎯 Focal — Responsive Focus Timer

[![Live Demo](https://img.shields.io/badge/Live-Demo-22c55e?style=for-the-badge)](https://your-vercel-link.vercel.app)

A distraction-free focus timer landing page, built with plain HTML5, CSS3, and vanilla JavaScript — no frameworks, no build step.

> **Project 1 — Responsive Frontend Interface**, DecodeLabs Full Stack Internship (Batch 2026)

---

## 📖 Overview

Focal is a single-page site where the hero itself is a working product: a live countdown ring that runs real focus/break cycles, not a screenshot standing in for one. The rest of the page — how it works, features, FAQ — supports that one job.

---

## 🌐 Live Demo

🔗 **Deployed Website:** https://your-vercel-link.vercel.app

> Replace the above URL with your deployed Vercel/Netlify/GitHub Pages link.

---

## ✨ Features

- ⏱️ **Live focus timer** — 15 / 25 / 50-minute sessions with an animated progress ring
- 🔁 **Automatic breaks** — switches to a 5-minute break after each session, 15 minutes after every fourth
- 📊 **Daily session count** — tracked locally per day, no account required
- 🌗 **Light / dark mode** — toggle in the header, remembered on return visits
- 📱 **Mobile-first responsive layout** — single column on phones, expands at tablet (768px) and desktop (1024px) breakpoints
- ♿ **Accessible by default** — semantic landmarks, visible focus states, `prefers-reduced-motion` support, skip link
- 🧩 **Accordion FAQ** and animated **hamburger navigation** with no external libraries

---

## 🛠️ Tech Stack

| Layer | Choice |
| ------ | ------ |
| Markup | Semantic HTML5 |
| Styling | CSS3 — Grid, Flexbox, Custom Properties, `clamp()` |
| Behavior | Vanilla JavaScript (ES6+) |
| Fonts | Montserrat (display) · Roboto (body) |
| Storage | `localStorage` (theme + daily session count) |

---

## 📸 Screenshots

### Hero / Timer (Desktop)

![Hero Screenshot](docs/screenshots/hero-desktop.png)

> Save the screenshot as `docs/screenshots/hero-desktop.png`.

---

## 📁 Folder Structure

```text
focal/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── docs/
│   └── screenshots/
│       └── hero-desktop.png
└── README.md
```

---

## 🚀 Installation & Running

No build tools or dependencies — it's a static HTML/CSS/JS project.

```bash
# Clone the repository
git clone <your-repo-url> focal

# Navigate into the project
cd focal

# Open directly
open index.html          # macOS
# or double-click index.html

# (Optional) Run a local server
npx serve .

# or

python3 -m http.server 5500
```

---

## 🧭 Usage

1. Choose a focus duration (15, 25, or 50 minutes).
2. Click **Start** to begin the countdown.
3. Watch the animated progress ring as the timer runs.
4. After a focus session ends, Focal automatically starts a break timer.
5. Toggle between light and dark mode anytime using the header switch.
6. Your theme preference and daily completed sessions are automatically saved in your browser.

---

## 🔮 Future Improvements

- Custom session lengths instead of fixed presets
- Optional sound or desktop notifications when a session ends
- Session history with weekly and monthly statistics
- Keyboard shortcuts for timer controls
- Multiple productivity themes and accent colors

---

## 👩‍💻 Author

**Tanya Vaish**

Full Stack Development Intern  
DecodeLabs (Batch 2026)