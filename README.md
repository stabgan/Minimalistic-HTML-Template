# Minimalistic HTML Template

A clean, lightweight multi-page HTML/CSS website template — no frameworks, no JavaScript, just semantic markup and modern CSS.

## What It Does

Provides a ready-to-use static website skeleton with four pages:

- **Home** — welcome / landing page
- **About** — informational page
- **Services** — service listing with cards
- **Contact** — form with name, email, and message fields

Each page shares a consistent navigation bar, sidebar, and footer.

## Architecture

```
index.html        ← Home page
about.html         ← About page
services.html      ← Services listing
contact.html       ← Contact form
style.css          ← Shared stylesheet (flexbox layout, responsive)
```

No build step required. Open `index.html` in any browser.

## 🛠 Tech Stack

| Tech | Purpose |
|------|---------|
| 🌐 HTML5 | Semantic markup (`<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`) |
| 🎨 CSS3 | Flexbox layout, responsive design with media queries |

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/stabgan/Minimalistic-HTML-Template.git
   ```
2. Open `index.html` in your browser — that's it.

To customize, edit the HTML content and tweak `style.css` to match your brand.

## ⚠️ Known Issues

- The contact form has no backend — submissions go nowhere. Wire it up to a service like [Formspree](https://formspree.io) or your own server.
- "Read More" links on the Services page are placeholder anchors (`#`).

## License

MIT
