## Project Overview

This project builds a responsive **Meet Landing Page** based on a high-fidelity design from Frontend Mentor. It emphasizes clean, component-based SCSS architecture, mobile-first layout strategy using Flexbox, and best practices for responsive imagery and accessibility.

- Responsive layout across mobile, tablet, and desktop breakpoints
- Semantic HTML5 structure with ARIA-aware components
- Flexbox-based layout architecture (no external frameworks)
- Scalable SCSS partials (BEM naming, tokens, and modular structure)
- Responsive image handling via `<picture>` and `srcset`
- [Link to Frontend Mentor Challenge](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR)

---

## Technologies Used

- HTML5
- CSS3 (Flexbox, Media Queries)
- SCSS (Partials, Variables, Mixins, BEM) – [Sass Docs](https://sass-lang.com/documentation)
- GitHub Pages (for live deployment)
- Figma (for design implementation)

---

## Screenshots

| Desktop View                                                       | Mobile View                                                      |
| ------------------------------------------------------------------ | ---------------------------------------------------------------- |
| ![Desktop screenshot](./assets/screenshots/desktop_screenshot.png) | ![Mobile screenshot](./assets/screenshots/mobile_screenshot.png) |

> 📸 _Screenshots to be added after final polish and QA pass_

---

## Folder Structure

<pre> ```bash meet-landing-page/ ├── index.html ├── assets/ │ ├── images/ │ ├── fonts/ │ └── screenshots/ ├── src/ │ └── styles/ │ ├── abstracts/ │ │ ├── _variables.scss │ │ ├── _mixins.scss │ │ └── _typography.scss │ ├── base/ │ │ ├── _reset.scss │ │ └── _global.scss │ ├── components/ │ │ ├── _button-blue.scss │ │ ├── _button-purple.scss │ │ ├── _logo.scss │ │ └── _number.scss │ ├── layout/ │ │ ├── _nav.scss │ │ ├── _hero.scss │ │ ├── _main-content.scss │ │ └── _footer.scss │ └── main.scss ├── README.md ``` </pre>

---

## Getting Started

1. Clone the repository:
   `git clone https://github.com/yourusername/meet-landing-page.git`

2. Navigate to the project directory:
   `cd meet-landing-page`

3. Compile SCSS to CSS (if using the CLI):
   `sass src/styles/main.scss style.css`

4. Open `index.html` in your browser to preview the layout.

---

## Key Learning Objectives

- Practice building a multi-section landing page using semantic HTML and Flexbox
- Learn to serve optimized, responsive images using the `<picture>` element
- Strengthen SCSS partial organization and design token usage
- Understand responsive layout shifts across devices
- Explore cross-browser consistency and hover state handling

---

## Improvements for the Future

- Implement mobile navigation toggle using vanilla JS or framework integration
- Add animated transitions for button hover states
- Perform full accessibility audit (Lighthouse + axe-core)
- Explore converting to a reusable component-based system (React or Angular)

---

## Time Estimation

| Task                              | Estimated Time |
| --------------------------------- | -------------- |
| Repo Initialization + Setup       | 30 mins        |
| SCSS Architecture + Base Styles   | 1.5 hours      |
| Layout Structure (HTML + Flexbox) | 2–3 hours      |
| Responsive Image Handling         | 1.5 hours      |
| Design Polish + QA                | 1.5 hours      |
| Total Estimated Time              | ~7–8 hours     |
