# DEVCONF2026 — Landing Page

**Assignment 1 · Full Stack Web Development Course · Programming Hero**

A landing page for a fictional developer conference, DEVCONF2026, built to practice core HTML5 and CSS3 fundamentals — semantic structure, Flexbox, Grid, and typography systems — with no JavaScript and no CSS frameworks.

---

## 📌 About the Project

DEVCONF2026 is a single-page conference site themed around the tagline **"Code. Connect. Create."** It includes a hero banner, a speaker showcase, tiered pricing cards, a "Why Attend" highlights section, and a footer — all styled from a single custom stylesheet.

This was built as the first assignment for Programming Hero's Full Stack Web Development course, focused on demonstrating clean semantic markup and CSS layout techniques without relying on any external UI libraries.

---

## 🛠️ Tech Stack

- **HTML5** — semantic elements, no frameworks
- **CSS3** — Flexbox, Grid, custom properties-free styling, media queries
- **Google Fonts** — Inter, Nunito, Arima
- ❌ No JavaScript
- ❌ No CSS frameworks or libraries (Bootstrap, Tailwind, etc.)

---

## 📂 File Structure

```
devconf2026/
├── index.html
├── style.css
├── assets/
│   ├── logo.png
│   ├── banner.jpg
│   ├── andrej.png
│   ├── demis.png
│   ├── gary.png
│   └── mustafa.png
├── prompts.md
└── README.md
```

---

## ✨ Sections

| Section | Description |
|---|---|
| **Header / Nav** | Logo, nav links, and a "Register Now" CTA |
| **Hero** | Full-bleed banner image with headline and CTA button |
| **Speakers** | Grid of speaker cards with field, name, and role |
| **Pricing** | Three-tier pricing cards (Standard / Pro / Team) |
| **Why Attend** | CSS Grid bento-style mosaic combining stats, a testimonial, and a workshop highlight |
| **Footer** | Copyright and legal links |

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary navy | `#0D1B2A` |
| Primary blue | `#2563EB` |
| Accent light blue | `#93C5FD` |
| Body text gray | `#575757` |
| Muted gray | `#888888` |
| Border gray | `#E5E7EB` |
| Border radius | `12px` (cards), `10px` (buttons) |
| Fonts | Inter (body), Nunito (nav) |

---

## 🚀 Running Locally

No build step or dependencies required.

1. Clone or download this repository
2. Open `index.html` directly in a browser, **or**
3. Serve it locally for a cleaner dev experience:
   ```bash
   npx serve .
   ```
   or use VS Code's Live Server extension

---

## ⚠️ Known Limitations

- Nav links and CTA buttons point to placeholder `#` anchors
- No JavaScript means some interactions (e.g. real-time countdowns, tabbed panels) were intentionally left out to stay within the assignment's constraints
- Layout is only responsive at one breakpoint (`768px`, added for the bento section) — the rest of the page assumes a desktop viewport

---

## 👤 Author

**Rajon**
Full Stack Web Development — Programming Hero
