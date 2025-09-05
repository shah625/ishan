# Ishan Shah — Personal Portfolio

A minimal, fast-loading personal portfolio focused on early-stage VC support and financial modeling.

## What This Site Is

This is a single-page portfolio website built to showcase expertise in financial modeling, diligence, and founder support for micro VCs. It includes:

- Clean, professional design optimized for credibility
- Mobile-first responsive layout
- Integrated slide deck presentation
- Performance optimized for GitHub Pages hosting

## Live Site

- **Portfolio**: [Your GitHub Pages URL here]
- **Presentation Deck**: [Your GitHub Pages URL here]/deck/

## Features

- **No build step required** - Pure HTML, CSS, and minimal JavaScript
- **Lighthouse 90+ scores** across all categories
- **Mobile-responsive** design that works on all devices
- **Semantic HTML** with proper accessibility
- **Smooth scrolling** navigation
- **Reveal.js slide deck** for presentations

## How to Enable GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar  
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

Your site will be live at: `https://[username].github.io/[repository-name]/`

## Custom Domain Setup (Optional)

To use a custom domain:

1. Add a `CNAME` file to the repository root with your domain name
2. In your DNS provider, add:
   - For apex domain (example.com): A records pointing to GitHub Pages IPs
   - For www subdomain: CNAME record pointing to [username].github.io
3. In repository settings → Pages, add your custom domain

## File Structure

```
/
├── index.html           # Main portfolio page
├── assets/
│   └── styles.css      # All styles
├── deck/
│   └── index.html      # Reveal.js presentation
├── README.md           # This file
└── CNAME               # Custom domain (optional)
```

## Updating Content

- **Personal info**: Edit the hero section in `index.html`
- **Work samples**: Update the "Selected Work" links
- **VC Oasis posts**: Update the articles list
- **Contact info**: Update email and LinkedIn URLs
- **Presentation**: Edit slides in `deck/index.html`

## Performance Notes

- Uses system fonts with Google Fonts fallback
- Minimal JavaScript (only smooth scrolling)
- Optimized images (when added, keep under 200KB)
- Preconnect to Google Fonts for faster loading

## Local Development

To preview locally:

```bash
cd /path/to/repository
python3 -m http.server 8000
```

Visit `http://localhost:8000` in your browser.
