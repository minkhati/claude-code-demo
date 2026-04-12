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

- [ ] Commit styles.css and updated index.html
- [ ] Push to origin/main

## Separate CSS — Review

Moved all styles from the inline `<style>` block in `index.html` into a new `styles.css` file. Replaced the `<style>` block with a single `<link rel="stylesheet" href="styles.css" />`. No styles were changed — purely structural separation.

## Push to GitHub — Review

Committed `claude.md` (workflow instructions) and pushed to `git@github.com:minkhati/claude-code-demo.git` on `main`. No other changes were needed — the remote and branch were already configured.

## Review

Created `index.html` — a single-file AI educational website for "Neuron". Sections: sticky navbar, hero with badge overlay, stats bar, 3-course grid, 2 feature rows, 3 testimonial cards, CTA banner, 4-column footer. Uses Inter (Google Fonts), placehold.co images, CSS Grid/Flexbox, no JS. Fully responsive down to 375px.
