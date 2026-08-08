# Meera Iyer — Portfolio

A single-page personal portfolio website built with **pure HTML and CSS** — no JavaScript, no frameworks, no build tools. Just open `portfolio.html` in a browser.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

## ✨ Features

- **Fully responsive** — scales cleanly from mobile to desktop using `clamp()`, CSS Grid, and Flexbox
- **No JavaScript** — the mobile hamburger menu is built entirely with the CSS "checkbox hack"
- **Modern, vibrant design** — warm color palette (violet, coral, teal, gold) instead of the typical dark theme
- **Custom typography** — Fraunces (display serif) paired with Plus Jakarta Sans (body) via Google Fonts
- **Signature visual touch** — an organic "blob" shaped photo frame in the About section
- **Accessible by default** — visible focus states and `prefers-reduced-motion` support
- **Sections included**: Hero, About, Skills, Selected Work, Contact

## 📁 Project structure

```
.
├── portfolio.html   # Page markup
├── styles.css        # All styling
└── README.md
```

## 🚀 Getting started

No installation or build step required.

1. Clone the repo
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `portfolio.html` directly in your browser, **or** serve it locally:
   ```bash
   # Python
   python3 -m http.server

   # or Node
   npx serve
   ```
3. Visit `http://localhost:8000` (or whatever port your server prints).

## 🎨 Customizing

| What to change | Where |
|---|---|
| Name, tagline, bio copy | `portfolio.html` — hero, about, and contact sections |
| Colors | `:root` variables at the top of `styles.css` |
| Fonts | `<link>` tags in `<head>` of `portfolio.html` + `font-family` values in `styles.css` |
| Profile photo | `<img>` src inside `.blob-frame` in `portfolio.html` |
| Hero background image | `background-image` under `.hero` in `styles.css` |
| Projects | Duplicate/edit `.card` blocks inside the `#work` section |
| Social links | `.socials` block in the footer |

## 🌐 Deploying

This is a static site, so it works out of the box with:

- **GitHub Pages** — Settings → Pages → Deploy from branch → `main` → `/root`
- **Netlify / Vercel** — drag-and-drop the folder or connect the repo
- Any static file host

## 📄 License

Free to use and adapt for your own portfolio.
