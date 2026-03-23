# Polia — Website Goals

## Purpose
Polia is a small company whose mission is making science and science-based tools more accessible to everyone. The website at **polia.nl** serves as a central hub linking all Polia-built tools and projects, with a simple way for visitors to support ongoing development.

## Brand
- **Name:** Polia
- **Tagline:** "for accessible science"
- **Tone:** Clean, minimal, trustworthy — science-adjacent without being cold or academic
- **Colors:** Derived from the Polia logo (see logo file in this folder)

## Page Structure
One single HTML page. No navigation menu, no sub-pages.

### 1. Header
- Polia logo centered at top
- Company name "Polia" as a heading beneath it
- Tagline: *"for accessible science"*

### 2. Tools / Projects
Three project cards or link blocks, each with:
- A short name and one-line description
- A clear call-to-action link

| Tool | Description | URL |
|---|---|---|
| Q-Method Tool | A hosted platform for running Q-methodology studies | https://qmethod.polia.nl/ |
| Nitrogen Footprint Calculator | Calculate your personal nitrogen footprint | https://my-nprint.web.app/ |
| NitroGenius (Game) | A science game about nitrogen — available in English and Dutch | EN: https://berentbaris.github.io/NitroGeniusWebGL/ / NL: https://berentbaris.github.io/NitrogeniusWebGL-Dutch/ |

### 3. Footer
- Small "Support development" section with a link to GitHub Sponsors (placeholder — final URL TBD)
- Minimal copyright line: © Polia

## Technical Requirements
- Single `.html` file (self-contained: CSS and JS inline, no external dependencies except optional Google Fonts)
- Fully responsive (mobile-friendly)
- No frameworks, no build step — deployable as a static file on GitHub Pages
- Color palette extracted from the logo file present in the folder
- Accessible: proper alt text, semantic HTML, good contrast ratios

---

## Current Status
**Last updated:** 2026-03-23

### Completed
- [x] Extract color palette from logo (teal range: #042a33 → #1a5962 → #a5ede9)
- [x] Build full `index.html` — header with embedded logo, tagline, three tool cards, footer with sponsor link
- [x] Responsive layout (mobile-friendly, stacks on small screens)
- [x] Fonts: DM Serif Display for headings, Inter for body
- [x] Logo base64-embedded for zero external image dependencies
- [x] Review & polish: WCAG AA contrast verified on all text pairs, footer color fixed (#587075), focus styles added for keyboard nav, HTML structure validated, accessibility checklist passed

### Next task
**Website is functionally complete.** Remaining items are owner decisions (see blockers below). After those are resolved, the site is ready to deploy to GitHub Pages.

### Blockers / decisions needed
- **GitHub Sponsors URL:** The footer currently links to `https://github.com/sponsors/` (placeholder). Needs the actual sponsor profile URL.
- **Design choice:** The logo already contains the word "Polia", so I omitted a separate `<h1>Polia</h1>` heading to avoid visual repetition. The `<h1>` is set as visually hidden (screen-reader accessible). If a visible heading is preferred below the logo, let me know.
