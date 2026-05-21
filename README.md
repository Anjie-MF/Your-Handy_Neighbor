# Your Handy Neighbor

A responsive, multi-page marketing website for a local handyman service. Built as a front-end practice project to develop core HTML, CSS, and responsive design skills.

**[Live Demo](https://anjie-mf.github.io/Your-Handy_Neighbor/index.html)** 

---

## About the Project

This project gave me hands-on experience building a real-world style business website from scratch. The goal was to practice structuring a multi-page site, writing responsive CSS without a framework, and working with a proper development toolchain.

---

## Pages

- **Home** — Hero section, services overview with Font Awesome icons, and a customer review
- **About** — Mission statement, crew profiles with photos, and an embedded Google Map
- **FAQ** — Common customer questions in a clean two-column layout

---

## Built With

- **HTML5** — Semantic markup throughout
- **CSS3** — Flexbox-based layouts, custom styles, no CSS framework
- **JavaScript** — Minimal; console error polyfill via plugins.js
- **[Parcel](https://parceljs.org/)** — Module bundler and local dev server
- **[Google Fonts](https://fonts.google.com/)** — Oswald & Raleway
- **[Font Awesome](https://fontawesome.com/)** — Service icons
- **[HTML5 Boilerplate](https://html5boilerplate.com/)** — Project foundation and normalize.css

---

## Features

- **Responsive design** across three breakpoints: mobile, tablet (768px+), and desktop (1200px+)
- **Mobile-first CSS** — base styles target small screens, media queries layer up
- **Multi-page navigation** with consistent header and footer across all pages
- **Embedded Google Map** with a responsive aspect-ratio container
- **Crew profiles** in a flexible photo grid

---

## What I Learned

- How to structure a multi-page site and manage relative file paths
- Writing responsive layouts with Flexbox — no Grid, no framework
- Why mobile-first CSS makes scaling up cleaner than scaling down
- Setting up a basic build workflow with npm and Parcel
- Reading and adapting a professional boilerplate rather than starting from zero

---

## Getting Started

```bash
git clone https://github.com/your-username/your-handy-neighbor.git
cd your-handy-neighbor
npm install
npm run dev
```

Open [http://localhost:1234](http://localhost:1234) to view in your browser.

To build for production:

```bash
npm run build
```

---

## Project Structure

```
├── index.html          # Homepage
├── about/
│   └── index.html      # About page
├── faq/
│   └── index.html      # FAQ page
├── css/
│   ├── main.css        # All custom styles
│   └── normalize.css   # Cross-browser reset
├── js/
│   ├── main.js
│   └── plugins.js
└── img/                # Site images
```

---

## Roadmap / What I'd Improve Next

- [ ] Add a working contact form
- [ ] Improve accessibility (ARIA labels, focus styles, alt text audit)
- [ ] Replace placeholder lorem ipsum with real copy
- [ ] Optimize images for faster load times
- [ ] Add CSS custom properties (variables) for the color palette

---

## Author

**Anjelica MF**
[GitHub](https://github.com/Anjie-MF) · [LinkedIn](https://www.linkedin.com/in/anjiemay23/)
