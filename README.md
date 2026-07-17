# Alexander Lindt — Portfolio

Personal portfolio website of **Alexander Lindt**, freelance web designer based in Ingolstadt, Germany.

A single-page, statically-served portfolio with a hand-crafted paper/collage visual style — layered paper textures, cut-out stickers, hand-drawn arrows and highlights — showcasing selected client and personal projects.

## ✨ Features

- **Single-page design** with a distinctive paper-collage aesthetic
- **Featured project showcase** (web apps, games, and client sites)
- **Responsive layout** for desktop and mobile
- **Custom typography** via Google Fonts (Bricolage Grotesque, Dancing Script, Sacramento, Kalam)
- **Legal pages** (Imprint / Privacy) rendered from the same page
- JavaScript-driven content rendering and interactive image slots

## 🛠️ Tech Stack

- **HTML5** — semantic page structure (`index.html`)
- **CSS** — inline/component styling with a custom collage design language
- **Vanilla JavaScript** — content rendering and interactions
  - `support.js` — page runtime and content data
  - `image-slot.js` — image slot handling
- **Google Fonts** — web typography

No build step required — it is a static site.

## 🚀 Getting Started

Clone the repository and open the page locally:

```bash
git clone https://github.com/alexlindt-arch/portfolio.git
cd portfolio
```

Then either open `index.html` directly in a browser, or serve it with any static server:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Visit `http://localhost:8000`.

## 📁 Project Structure

```
portfolio/
├── index.html        # Main portfolio page
├── support.js        # Page runtime + content data
├── image-slot.js     # Image slot handling
├── assets/           # Images: portraits, project shots, textures, stickers
└── README.md
```

## 👤 Author

**Alexander Lindt** — Freelance Web Designer, Ingolstadt
📧 alexanderlindt16@outlook.de

---

© Alexander Lindt. All rights reserved.
