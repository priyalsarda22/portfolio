# Portfolio Website

A minimalistic portfolio website for showcasing biomedical engineering projects.

## Setup for GitHub Pages

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Under "Source", select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Click Save

Your site will be live at `https://yourusername.github.io/repository-name/`

## Customization

### Personal Information
Edit `index.html` to update:
- Your name in the `<title>` tag and hero section
- Logo initials in the nav
- About section text
- Contact information and links

### Projects
Each project is a `project-card` div. Modify:
- Project title
- Description
- Technology tags in `tech-stack`

### Styling
Edit `styles.css` to customize:
- Colors (primary color is #333)
- Fonts
- Spacing
- Card styles

## Structure

```
/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
└── README.md       # This file
```

## Features

- Responsive design (mobile-friendly)
- Smooth scrolling navigation
- Clean, minimalistic aesthetic
- Project cards with hover effects
- No external dependencies
