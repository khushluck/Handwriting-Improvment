# Handwriting Improvement

An Apple-inspired interactive website for improving handwriting with the Pentel EnerGel pen.

## Features

- **Pen Storytelling** — Scroll-driven fixed-pen animation through 4 narrative sections (GSAP + ScrollTrigger)
- **Product Showcases** — 4 full-viewport Apple-style sections (Smooth Ink Flow, Comfortable Grip, Precision Tip, Fast Drying Ink)
- **Pen Hotspots** — Interactive explorer with 4 animated hotspots over the pen image
- **AI Handwriting Analyzer** — Upload a handwriting sample for canvas-based pixel analysis across consistency, spacing, slant, and pressure
- **Before/After Slider** — Draggable clip-path comparison with notebook-paper styling
- **Practice Sheet Generator** — Custom practice sheets (letters/words/sentences, lined/grid/dotted paper, 3 difficulty levels)
- **30-Day Challenge** — Track daily handwriting tasks with localStorage persistence
- **Progress Tracker** — 10-goal checklist with real-time progress bar
- **Dark Mode** — Light/Dark/System toggle with localStorage persistence
- **Reading Progress Bar** — Fixed 3px gradient bar showing scroll progress
- **Statistics Counter** — Animated numbers (tips, exercises, words, days) that count up on scroll
- **Handwriting Journey Timeline** — 5 milestones with staggered slide-in animation
- **Sticky Tips Navigator** — Glassmorphism sidebar auto-highlighting the current tip
- **20 Detailed Tips** — Comprehensive handwriting improvement guide with subsections
- **Premium Glass Footer** — 4-column grid with glassmorphism design

## Tech Stack

- HTML5, CSS3 (custom properties, glassmorphism, grid/flexbox)
- GSAP 3.12.5 + ScrollTrigger (scroll animations, pinning, timeline sequencing)
- JavaScript (vanilla, canvas-based image analysis, localStorage persistence)
- Apple design system (San Francisco font stack, aurora backgrounds, pill buttons)

## Usage

Open `index.html` in a browser. No build step or server required.

The pen image (`pentel-energel.png`) must be in the same directory as `index.html`.

## Project Structure

```
├── index.html              # Main HTML + all JavaScript
├── liquid-glass.css        # Complete design system (3095 lines)
├── pentel-energel.png      # Pen image (scroll story + hotspots)
└── README.md
```

## Credits

- Pentel EnerGel pen imagery
- GSAP by GreenSock
