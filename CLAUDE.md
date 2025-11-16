# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static portfolio website for a biomedical engineer. Pure HTML/CSS with no build tools, frameworks, or dependencies. Designed for GitHub Pages hosting.

## Development

**Local preview:** Open `index.html` directly in a browser, or use any static server:
```bash
python -m http.server 8000
# or
npx serve .
```

**Deployment:** Push to GitHub, enable Pages in repository settings (Settings > Pages > Deploy from branch > main).

## Architecture

- `index.html` - Single-page application with sections: hero, about, projects, contact
- `styles.css` - All styling including responsive breakpoints at 768px and 480px
- No JavaScript, no build process, no external dependencies

## Key Patterns

- Project cards follow consistent structure: `.project-card` with icon, title, description, and `.tech-stack` tags
- CSS uses system font stack (`-apple-system, BlinkMacSystemFont...`)
- Primary color is `#333`, backgrounds alternate between `#fff` and `#fafafa`
- Fixed navigation with blur backdrop filter
- Smooth scroll behavior enabled globally
