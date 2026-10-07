# Taylor Poe — Personal Website

Professional portfolio and resume site for **Taylor Poe**, CTO of **PARTNER BioResearch** and a hands-on technical leader working across full-stack engineering, applied AI, systems architecture, and UI/UX.

**Live:** https://tpoe25.github.io  
**LinkedIn:** https://www.linkedin.com/in/tpoe25  
**GitHub:** https://github.com/TPoe25

## Positioning

The site is designed to communicate senior technical leadership quickly without turning into a long-form resume or exposing sensitive project details.

It focuses on four signals:

- CTO leadership and technical strategy
- Full-stack and systems architecture capability
- Applied AI with clear guardrails and human decision points
- Product/UI/UX judgment that makes complex systems easier to use

## What’s Included

- Executive hero with current CTO role
- Technical leadership summary
- Capability matrix spanning engineering, AI, UI/UX, and architecture
- Selected work presented at an intentionally abstract level
- Interactive architecture lab built with lightweight JavaScript
- Experience and education timeline
- Professional links and downloadable resume

## Tech Stack

- Semantic HTML5
- Modern CSS with custom design tokens
- Vanilla JavaScript
- Responsive, accessible layout
- GitHub Pages hosting

No application framework is required. The site is intentionally lightweight and keeps runtime dependencies to a minimum.

## Design Direction

The visual system is a restrained technical/executive aesthetic rather than a traditional developer-template portfolio:

- Deep navy surfaces with indigo/cyan accents
- High-contrast editorial typography
- Glass and grid effects used sparingly
- Strong spacing and hierarchy for resume scanning
- Interactive elements used as evidence of engineering judgment, not decoration
- Responsive behavior across desktop, tablet, and mobile
- `prefers-reduced-motion` support and visible focus states

## Project Privacy

Current venture work is intentionally described at the system-pattern level. The goal is to demonstrate architecture, engineering, product, and AI thinking without publishing sensitive implementation details.

## Local Development

Because the project is static, you can open `index.html` directly or serve the directory with any local static server.

Example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

GitHub Pages deploys from the `main` branch.

```bash
git add .
git commit -m "Refresh CTO portfolio"
git push origin main
```

## Repository Structure

```text
.
├── index.html
├── styles.css
├── resume.pdf
├── readme.md
└── images/
    ├── profile.jpg
    └── incisight-cover.png
```

## Design Goal

This site should feel like the homepage of a technical executive who can still build: clear enough for recruiters and partners to scan quickly, detailed enough for engineers to recognize depth, and polished enough to represent leadership-level work.
