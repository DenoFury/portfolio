# Portfolio

My personal portfolio site — a single-page, dark-themed site showcasing my projects, background, and skills, built from scratch with plain HTML and CSS (no frameworks).

**[Live site](https://denofury.github.io/portfolio/)**

## Features
- Single-page layout with anchor-linked navigation (About, Projects, Skills, Contact)
- Dark, minimal design with a small, deliberate color palette
- Project cards linking out to my other repos (Task Manager CLI, Weather Dashboard CLI)
- Fully responsive-ready structure (single column by design)

## Tech Stack
- HTML — semantic structure (`header`, `main`, `section`, `article`, `nav`)
- CSS — Flexbox layout, CSS custom properties (variables) for theming, no external frameworks or libraries

## Installation
```bash
git clone https://github.com/DenoFury/portfolio.git
cd portfolio
```
Open `index.html` directly in a browser — no build step required.

## Design
- **Palette**: a small, deliberately restrained set of colors defined as CSS custom properties (`--text-main`, `--text-muted`, `--text-accent`, `--surface`, `--border`), each used for a consistent *purpose* across the page rather than assigned per-section.
- **Accent color** is reserved specifically for project links and nav hover states, kept rare on purpose so it stays meaningful rather than becoming visual noise.
- **Type scale**: a single `<h1>` (my name) as the page's primary heading, with consistent `<h2>` section headings throughout — deliberate one-heading-per-page hierarchy rather than competing headings.

## Future Improvements
- Add screenshots/preview images to each project card
- Multi-column layout for wider screens
- Small scroll-reveal or hover animations
- Move to a proper build setup if the site grows beyond a single page

## Lessons Learned
First project focused entirely on frontend structure and design rather than logic. Learned to be deliberate about semantic HTML — when `<article>` fits versus `<p>`, when `<nav>` is actually appropriate versus just a plain link — and to treat a color palette as a functional system (each color has one job) rather than decorating page sections individually. Also the first project using CSS custom properties and Flexbox for real, purposeful layout control instead of default block stacking.
