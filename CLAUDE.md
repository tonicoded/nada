# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**nada** is a minimalist crypto coin website with the tagline "a coin about nothing". The project embraces an intentionally ugly, handwritten aesthetic with deadpan humor throughout.

## Development Commands

This is a static HTML/CSS/JS website with no build process:

```bash
# Serve locally (any simple server)
python -m http.server 8000
# or
npx serve .

# No build, test, or lint commands - intentionally minimal
```

## Architecture & Design Philosophy

- **Single-page website**: All content in `index.html`
- **Inline everything**: CSS and JS are embedded for simplicity
- **Under 50kb total**: Performance through minimalism
- **Black & white only**: No colors, gradients, or shadows
- **Handwritten aesthetic**: Using Kalam font, crooked alignment, wobbly elements
- **Self-aware humor**: Deadpan copy about having "nothing"

## Key Files

- `index.html` - Main website with all sections
- `404.html` - Custom 404 page ("page not found. like everything else.")
- `CLAUDE.md` - This file

## Content Guidelines

- **Always lowercase**: All copy should be lowercase
- **Deadpan tone**: Dry, self-aware, absurdist humor
- **No promises**: Never claim utility, roadmaps, or features
- **Embrace ugly**: Crooked elements, misaligned text, wobbly borders
- **SVG doodles**: Hand-drawn style arrows, boxes, stick figures

## Visual Elements

- Handwritten font (Kalam from Google Fonts)
- Random rotations on sections (-2deg to +2deg)
- Strikethrough text for "promises we don't make"
- Inline SVG for doodles (arrows, empty boxes, stick figures)
- Button wiggle animation on hover
- Infinite loading spinner that never completes
- Progress bar that stops at 99%

## Interactive Features

- Buy button with wiggle animation (currently shows alert)
- Console easter eggs
- Random section rotations on page load
- Fake progress indicators

## Deployment

Deploy as static files to any host:
- GitHub Pages
- Vercel
- Netlify
- Simple file hosting

## Copy Library (for updates/social)

- "buy nothing, hold nothing, get nothing."
- "no utility. no problem."  
- "roadmap: we're not going anywhere."
- "updates: nothing happened."
- "we audited nothing. it passed."

## Important Notes

- Keep total file size minimal
- Never add actual crypto functionality - it's performance art
- Maintain the "ugly" aesthetic - avoid polishing
- All disclaimers should be deadpan but legally sound