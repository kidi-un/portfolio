# Vasanth A — Portfolio

> Personal developer portfolio of **Vasanth A** (Kidi), AI & Data Science final-year student — built as a single-file `index.html` with zero build tools and zero dependencies beyond Google Fonts.

🌐 **Live:** [kidi-un.github.io/portfolio](https://kidi-un.github.io/portfolio/)

---

## ✨ Features

| Feature | Details |
|---|---|
| **3D Hero Canvas** | Neural brain network + data orbit animation rendered with raw WebGL / Canvas API |
| **Custom Cursor** | Floating green dot with multi-trail effect |
| **Parallax & Scroll Animations** | Sections animate in on scroll using IntersectionObserver |
| **Magnetic CTA Buttons** | Buttons subtly follow the cursor on hover |
| **Skill Cube** | Interactive 3D cube with scroll-triggered Y-axis rotation and pixel-burst click animations |
| **Interactive Footer** | Particle / constellation canvas in the footer |
| **Noise Texture Overlay** | Subtle SVG fractalNoise layer for paper-like depth |
| **Scroll Progress Bar** | Thin gradient bar at the top of the viewport |
| **Marquee Ticker** | Animated horizontal text ticker between sections |
| **Google Fonts** | Crimson Pro · Sora · DM Mono |
| **Pure HTML/CSS/JS** | No frameworks, no bundlers — ships as one file |

---

## 🎨 Design System

```
Colors
  --paper    #f5f8f0   Background (light sage)
  --ink      #1a2010   Primary text
  --red      #65a30d   Accent green  (CTAs, dots, highlights)
  --gold     #b45309   Accent amber  (dividers, stamps)
  --muted    #4d6645   Secondary text

Typography
  Headings   → Crimson Pro (serif, italic variants)
  Body / UI  → Sora (geometric sans)
  Code / Mono → DM Mono
```

---

## 📁 Structure

```
portfolio/
└── index.html   # Everything — HTML, CSS, JavaScript in one file (1 706 lines)
```

The portfolio is intentionally a **single-file site** deployed via GitHub Pages. No `package.json`, no build step.

---

## 🚀 Running Locally

```bash
# Clone
git clone https://github.com/kidi-un/portfolio.git
cd portfolio

# Open directly in browser — no server needed
open index.html
# or
npx serve .
```

---

## 📄 Sections

1. **Nav** — Fixed top bar with status dot ("Available for work")
2. **Hero** — Name, tagline, tech tags, CTA buttons, 3D canvas
3. **About** — Bio, timeline, philosophy
4. **Skills** — Animated 3D skill cube + tag grid
5. **Projects** — Cards for QIBoneNet, OTA.ai, IoT Wearable, ISL Platform, FitPro, and more
6. **Research** — Publications and journal submissions
7. **Contact** — Email + socials + footer constellation canvas

---

## 🛠️ Tech Stack

- **Rendering:** Canvas 2D API, WebGL (raw)
- **Animations:** CSS keyframes + IntersectionObserver + requestAnimationFrame
- **Fonts:** Google Fonts (self-contained link tag)
- **Hosting:** GitHub Pages (branch: `main`, root `/`)

---

## 📬 Contact

| | |
|---|---|
| Email | vasanthprofjob@gmail.com |
| GitHub | [@kidi-un](https://github.com/kidi-un) |
| LinkedIn | [Vasanth A](https://linkedin.com/in/vasanth-a) |

---

<p align="center">Built with ☕ and too many Canvas API docs — Vasanth A © 2024</p>
