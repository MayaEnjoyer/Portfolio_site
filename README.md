<h1 align="center">
 <img src="Mai-Transparent-PNG.png">
  <br />
Description of the Portfolio Site project
</h1>

<p align="center"> 
A dark, multipage portfolio site with clean typography, responsive layout, and animations built on HTML + CSS with minimal Vanilla JS.
</p> 



**Live demo:** https://mayaenjoyer.github.io/Portfolio_site/  

---

### Table of Contents

- [What the project does](#what-the-project-does)
- [Features](#features)
- [Pages](#pages)
- [Project structure](#project-structure)
- [Tech stack](#tech-stack)


---

### What the project does

- Presents a personal portfolio with a consistent dark theme.
- Organizes content into clear sections/pages (About, Articles, Gallery, Catalog, etc.).
- Demonstrates common UI patterns: sticky header, responsive grid/flex, tabs, anchors, cards, badges.
- Includes a **canvas animation** (ASCII background) on the Register page and respects `prefers-reduced-motion`.

---

### Features

- **Dark theme** powered by CSS custom properties (`:root`). Easily tweak colors/radii.
- **Responsive layout:** grids/flexbox, sticky header, mobile navigation.
- **Gallery** with captions and clean frames.
- **Catalog** (categories/subcategories) with custom bullets and external links.
- **Anchor navigation:** table of contents, smooth scrolling, “Back to top”.
- **Articles:** `article.html` injects text based on `?slug=...` from the `POSTS` object.
- **Login/Register** tabs with **ASCII background** (canvas; respects `prefers-reduced-motion`).
- **Accessibility:** skip link, ARIA attributes, high-contrast focus states, `scroll-margin' for the sticky header.
- **Clean structure** that's easy to extend.

---

### Pages

- `index.html` — Home.
- `pages/about.html` — About Me.
- `pages/articles.html` — Articles list.
- `pages/article.html` — Single article (content chosen by `?slug=...`).
- `pages/gallery.html` — Image gallery.
- `pages/catalog.html` — Category/subcategory list with external links.
- `pages/anchors.html` — Anchors/sections demo with table of contents.
- `pages/contacts.html` — Contact form mock.
- `pages/register.html` — Login/Register tabs + ASCII canvas background.

---

### Project structure:

![Portfolio Site](Project%20tree.png)

---

### Tech stack

```
• HTML5, CSS3
• Minimal JavaScript (vanilla) for tabs and the canvas animation
• Deployed with GitHub Pages
```














































