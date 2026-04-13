---
name: Neuron AI Education Website
description: Static HTML/CSS landing page for an AI education platform. No JS files — purely HTML and CSS. Uses Google Fonts (Inter), placehold.co for placeholder images, CSS custom properties, and CSS grid layouts. No build system.
type: project
---

Static marketing/landing page. Two files: index.html and styles.css. No JavaScript. No backend. Key observations:

- All links are placeholder `#` hrefs — site is not yet wired up
- Images sourced from placehold.co (third-party placeholder service)
- Google Fonts loaded via preconnect + stylesheet link
- CSS uses custom properties (--var pattern) extensively
- No JS, so no XSS risk from dynamic DOM manipulation
- No forms, no user input, no data collection on the page itself
- Responsive via two media query breakpoints (960px, 600px)
- Mobile nav hidden at 960px with no hamburger menu replacement

**Why:** Context for future reviews of this project.
**How to apply:** Don't flag missing JS security controls — there is no JS. Do flag missing mobile nav, accessibility gaps, and third-party resource risks.
