# AI Educational Website — Todo

## Checklist

- [x] Write plan and get approval
- [x] Create `index.html` with navbar, hero, stats, courses, features, testimonials, CTA, footer
- [x] Verify layout in browser (all sections, placeholder images, responsive)

## Push to GitHub

- [x] Check git status and existing remotes
- [x] Commit untracked file (claude.md)
- [x] Push to GitHub remote (origin/main)

## Separate CSS into external file

- [x] Extract all CSS from <style> tag into styles.css
- [x] Update index.html to link styles.css via <link>
- [x] Verify index.html still renders correctly

## Push CSS refactor to GitHub

- [x] Commit styles.css and updated index.html
- [x] Push to origin/main

## Separate CSS — Review

Moved all styles from the inline `<style>` block in `index.html` into a new `styles.css` file. Replaced the `<style>` block with a single `<link rel="stylesheet" href="styles.css" />`. No styles were changed — purely structural separation.

## Push to GitHub — Review

Committed `claude.md` (workflow instructions) and pushed to `git@github.com:minkhati/claude-code-demo.git` on `main`. No other changes were needed — the remote and branch were already configured.

## Review

Created `index.html` — a single-file AI educational website for "Neuron". Sections: sticky navbar, hero with badge overlay, stats bar, 3-course grid, 2 feature rows, 3 testimonial cards, CTA banner, 4-column footer. Uses Inter (Google Fonts), placehold.co images, CSS Grid/Flexbox, no JS. Fully responsive down to 375px.

## UI Redesign — Beau inspiration

- [x] Update color system: lavender page background, pastel accent palette
- [x] Redesign navbar: softer feel, pill logo badge
- [x] Redesign hero: colorful abstract gradient illustration, rounder layout
- [x] Replace feature rows with bento-grid card layout
- [x] Redesign CTA as standalone rounded card with teal gradient
- [x] Add colorful gallery grid section
- [x] Update global styles: rounder corners, softer shadows, more spacing

## UI Redesign — Review

Overhauled both `styles.css` and `index.html` to match the Beau-inspired design:
- **Color system**: replaced plain white with `#edeaf7` lavender background; added teal, yellow, and coral as secondary accents
- **Navbar**: pill-shaped logo, hover-pill nav links, no border box
- **Hero**: CSS morphing blob shape with floating pill labels replaces the static placeholder image; badge repositioned bottom-right
- **Stats**: wrapped in a white rounded card that floats on the lavender bg
- **Bento features**: 3-column grid with a wide card, tall dark card, and three pastel mini-cards (yellow, teal, coral) replacing the two-column feature rows
- **Testimonials**: middle card uses purple fill for visual contrast
- **Gallery**: new 4-column section of colorful gradient cards with floating blob accents and label pills
- **CTA**: standalone teal-gradient rounded card with decorative circle overlays, yellow hover on the button
- **Global**: `--radius-lg` 28px, `--shadow` and `--shadow-lg` with purple tint, all inline styles moved to CSS classes
