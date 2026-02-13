# DESCRIPTION.md

This file provides guidance for working with this repository.

## Project Overview

**Midcoast Solidarity Website* - A simple website built with vanilla HTML, CSS, and JavaScript. No frameworks, no build step, no dependencies. Just open `index.html` in a browser.

## Files

- `index.html` - Main HTML structure
- `styles.css` - All styling with CSS variables and dark mode support
- `script.js` - All functionality
- `favicon.svg` / `favicon.png` - Site icons

## Development

No build step required. To develop:

1. Open `index.html` in a browser
2. Edit files and refresh

For live reload, use any simple HTTP server:
```bash
python -m http.server 8000
# or
npx serve
```

## Architecture

### State Management
All state is stored in a single `state` object in `script.js`:

### Data Persistence

### Image Processing

### CSS Variables
All colors, sizes, and shadows are defined as CSS variables in `:root` for easy theming. Dark mode is handled via `@media (prefers-color-scheme: dark)`.

## Key Features
- Dark mode (follows system preference)
- All data stored locally in browser