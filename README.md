# EcoHabits – Website Source Code

This repository contains the front-end source code (HTML and CSS) for **EcoHabits** (ecohabits.ie), a website built as part of our MSc Interactive Digital Media Dissertation by Practice at Griffith College.

**Live site:** [ecohabits.ie](http://ecohabits.ie)

## About the project

EcoHabits is a WordPress website that encourages small, everyday sustainability habits through short articles, videos, interactive quizzes, and simple browser games. The site was built using WordPress with the Astra theme, using WordPress's block editor and the Additional CSS panel, rather than a page builder plugin.

## Tech stack

- **CMS:** WordPress with the Astra theme
- **Page structure:** Custom HTML blocks (homepage, footer, Eco Tips cards, quiz pages) and native Gutenberg blocks (article pages)
- **Styling:** Hand-written CSS in the WordPress Customizer's Additional CSS panel (no CSS framework)
- **Fonts:** Fraunces (headings) and Plus Jakarta Sans (body text), loaded via Google Fonts
- **Quizzes:** QSM (Quiz and Survey Master) plugin
- **Interactivity:** p5.js (homepage animation and two mini-games)
- **Design/planning:** Figma (wireframes) and FigJam (sitemap, information architecture, team brainstorming)
- **Video/image content:** Canva

## File structure

Each page on the live site has a matching HTML file and, where relevant, its own CSS file. `additionalCSS.css` is the single global stylesheet applied across the entire site (typography, buttons, shared components, etc.) and works alongside the page-specific CSS files below.

| File | Live page |
|---|---|
| `homepage.html` / `homepage.css` | Homepage |
| `about.html` / `about.css` | About page |
| `ecotips.html` / `ecotips.css` | Eco Tips hub page |
| `quiz.html` / `quiz.css` | Take the Quiz page |
| `footer.html` | Site footer (used across all pages) |
| `additionalCSS.css` | Global stylesheet (fonts, buttons, shared components) applied site-wide |

## Note

This code was written directly inside WordPress (Custom HTML blocks and the Additional CSS panel) rather than developed in a local environment, so this repository is intended as a documentation/reference copy of the site's code rather than a deployable standalone project.
