# Personal Website

A high-impact personal website focused on bold visuals and interactive motion.

## Tech Stack

- HTML5 (semantic structure, single-page layout)
- CSS3 (custom properties, flexbox, grid, media queries, transitions, animations)
- JavaScript ES6+ (vanilla DOM APIs, IntersectionObserver, pointer interactions)
- Google Fonts (Monoton, Space Grotesk)

## Architecture

- Static frontend project (no framework, no build step)
- `index.html` for page structure
- `style.css` for visual style and animation system
- `script.js` for scroll reveal and pointer-based interactions

## Project Structure

```text
.
|-- index.html
|-- style.css
|-- script.js
`-- PRD.md
```

## Local Preview

Option 1: open `index.html` directly in a browser.

Option 2: run a local static server:

```bash
python -m http.server 4173
```

Then open `http://127.0.0.1:4173`.
