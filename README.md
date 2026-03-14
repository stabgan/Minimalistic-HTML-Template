# 🌐 Minimalistic HTML Template

A clean, lightweight, multi-page website template built with pure HTML and CSS — no frameworks, no dependencies, no build tools. Perfect as a starting point for simple static sites or for learning the fundamentals of web development.

> Originally created as a nostalgic first website project. Completely open source — use it however you like, no attribution required.

## ✨ Features

- 📄 Four ready-made pages: **Home**, **About**, **Services**, **Contact**
- 🧭 Consistent navigation bar with active-page highlighting
- 📬 Contact page with a simple form (name, email, message)
- 📦 Sidebar layout on every page
- 🎨 Dark-themed, minimal design out of the box
- ⚡ Zero dependencies — just open `index.html` in a browser

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| 📝 Markup | HTML5 |
| 🎨 Styling | CSS3 |
| 📐 Layout | Float-based, fixed-width (960 px) |

No JavaScript. No frameworks. No build step.

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/stabgan/Minimalistic-HTML-Template.git
   ```
2. **Open in your browser**
   ```bash
   open index.html        # macOS
   xdg-open index.html    # Linux
   start index.html       # Windows
   ```
3. **Customize** — edit the HTML files and `style.css` to make it your own.

### 📁 Project Structure

```
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services listing page
├── contact.html        # Contact form page
├── style.css           # Global stylesheet
└── A Simple HTML Template/   # (duplicate folder — see Known Issues)
```

## ⚠️ Known Issues

| # | Issue | Details |
|---|-------|---------|
| 1 | **Duplicate folder** | `A Simple HTML Template/` is an accidentally uploaded copy of the root files (noted in its own Readme). |
| 2 | **Not responsive** | Layout uses a fixed 960 px width; no media queries for mobile/tablet. |
| 3 | **Contact form has no backend** | The `<form>` on the contact page has no `action` or server-side handler — submissions go nowhere. |
| 4 | **Reused `name` attributes** | All form inputs in `contact.html` share `name="name"`, which would cause data conflicts on submission. |
| 5 | **Missing `<meta charset>` & viewport tag** | Pages lack `<meta charset="UTF-8">` and `<meta name="viewport" ...>` declarations. |
| 6 | **Copyright year hardcoded** | Footer reads "Copyright © 2016" on every page. |
| 7 | **Float-based layout** | Uses `float` for columns instead of modern Flexbox / CSS Grid. |

## 📜 License

Open source — free to use for any purpose.
