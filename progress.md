# Polia Website — Progress Log

## 2026-03-23 — Session 1: Initial build
- Extracted color palette from `polia-logo.png` (dominant teal: `#1a5962`, dark: `#104c56`, light: `#a5ede9`)
- Built complete `index.html`: header with base64-embedded logo, tagline, 3 tool cards (Q-Method, Nitrogen Footprint, NitroGenius), footer with sponsor placeholder
- Typography: DM Serif Display for card headings, Inter for body — loaded via Google Fonts
- Responsive: cards stack on mobile (<520px), logo scales with viewport
- Added visually-hidden `<h1>` for screen readers (logo already shows "Polia" text)

## 2026-03-23 — Session 2: Review & polish
- Ran WCAG AA contrast audit on all text/background pairs — all pass except footer copyright
- Fixed footer copyright color from `#8a9fa3` (2.73:1, FAIL) to `#587075` (5.17:1, PASS)
- Added `focus-within` style on cards and `focus-visible` on footer link for keyboard navigation
- Removed redundant media query (`min-width: 640px` that redeclared existing grid)
- Validated HTML structure (no unclosed tags) and accessibility checklist (lang, viewport, alt, aria-label, noopener)
