# Obscura Library 📚
**A Literary Bookstore UI — Vintage Aesthetic Web Interface**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 🔗 Live Demo
[**→ View Live Project**](https://ili1iml.github.io/Obscura-Library-Project/)

---


## 💡 About

**Obscura Library** is a front-end UI concept for an independent literary bookstore — designed with a warm, vintage aesthetic that feels like walking into an old bookshop. The design language centers around earthy greens and aged parchment tones, paired with classic serif typography to evoke the feel of print and paper.

Built as my fourth front-end project, focusing on multi-section page architecture, CSS design systems, scroll-based animations, and live search filtering.

---

## ✨ Features

- **Live Search** — Filters book cards in real time as you type, no page reload
- **Featured Book Section** — Hero-style spotlight with gradient background and book cover
- **Browse by Category** — 6-category grid with hover interactions
- **Books Grid** — Responsive 4-column layout with image zoom on hover and scroll-in animation
- **Intersection Observer** — Cards animate into view as the user scrolls down the page
- **Sticky Header** — Navigation stays fixed with search bar integrated in the header
- **Responsive Layout** — Adapts from 1 column (mobile) → 2 columns (tablet) → 4 columns (desktop)
- **Vintage Design System** — Consistent earthy palette and serif font stack (Playfair Display, Crimson Text, Libre Baskerville)
- **Smooth Scroll** — Anchor links scroll smoothly to their sections

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Semantic multi-section page structure |
| CSS3 | Design system with CSS variables, responsive grid, hover effects |
| Vanilla JavaScript | Live search, scroll animations, smooth scroll |
| Intersection Observer API | Scroll-triggered card entrance animations |
| Google Fonts | Playfair Display, Crimson Text, Libre Baskerville |

---

## 📂 Project Structure

```
obscura-library/
├── index.html       # Full page structure — header, sections, footer
├── styles.css       # Complete design system — variables, layout, responsive
├── script.js        # Live search, scroll animations, smooth scroll
├── images/          # Book cover images
└── README.md        # You are here
```

---

## 🚀 Getting Started

No installation or dependencies required.

```bash
# Clone the repository
[git clone](https://github.com/ili1iml/Obscura-Library-Project.git)

# Navigate into the folder
cd obscura-library

# Open in your browser
open index.html
```

---

## 🧠 What I Learned

- Building a **multi-section landing page** with a clear visual hierarchy across hero, categories, grid, and footer
- Creating a **CSS design system** using custom properties (`--color-primary`, `--bg-card`, etc.) for a consistent, easy-to-maintain theme
- Using the **Intersection Observer API** to trigger entrance animations only when elements enter the viewport — a performance-friendly alternative to scroll event listeners
- Implementing **live search filtering** by querying the DOM and toggling `display` based on text matching
- Pairing **multiple serif typefaces** deliberately (Playfair for headings, Crimson for body, Libre Baskerville for UI elements) to create typographic hierarchy
- Building a **fully responsive grid** that shifts columns at different breakpoints using only CSS Grid and `@media` queries

---

## 🗺️ Roadmap

- [ ] Add a book detail modal with full description and purchase CTA
- [ ] Implement category filtering alongside the live search
- [ ] Add a "Wishlist" feature using localStorage
- [ ] Build a shopping cart UI
- [ ] Rebuild with React — extract BookCard, CategoryCard, and Header as components
- [ ] Add a mobile hamburger menu (currently hidden on mobile)

---

## 👩‍💻 Author

**MOUDI ALOTAIBI**  
*Front-end developer in training — building a portfolio one project at a time*

---

> *"A reader lives a thousand lives before he dies. The man who never reads lives only one." — George R.R. Martin*
