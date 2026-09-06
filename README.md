# Marcello Zago - Personal Academic Website

A personal website built with [Quarto](https://quarto.org/) and deployed via GitHub Pages.

## Structure

```
.
├── _quarto.yml              # Website configuration
├── index.qmd               # Homepage
├── publications.qmd        # Research publications
├── cv.qmd                  # Curriculum Vitae
├── about.qmd               # Optional about page (unused)
├── images/                 # Profile picture and other images
│   └── profile.jpg         # Add your profile picture here
├── docs/                   # Rendered output (committed for GitHub Pages)
├── styles.css              # Custom CSS
├── header.html             # Custom HTML header
├── .gitignore              # Git ignore rules
└── .github/workflows/      # GitHub Actions
    └── deploy.yml          # Auto-deployment workflow
```

## Customization

### Quick Start

1. **Add your profile picture:** Place a `profile.jpg` (200x200px recommended) in the `images/` directory
2. **Edit your info:** Update placeholder text in `index.qmd`, `publications.qmd`, and `cv.qmd`
3. **Add CV PDF:** Place your `cv.pdf` in the repository root for embedding

### Adding Content

- **Homepage:** Edit `index.qmd`
- **Publications:** Edit `publications.qmd` - add/remove papers as needed
- **CV:** Edit `cv.qmd` or replace with your own PDF

### Styling

Custom styles are in `styles.css`. The theme uses:
- Professional blue accent colors
- Clean card-based layouts
- Responsive design for mobile

### Navigation

Edit `_quarto.yml` to change the navbar links.

## Local Development

```bash
# Render the site
quarto render

# Preview locally (auto-refreshes on changes)
quarto preview
```

## Deployment

1. Commit and push all changes to `main` branch
2. GitHub Actions will automatically build and deploy to GitHub Pages
3. Site will be available at https://MarcelloZago.github.io

## GitHub Pages Configuration

- **Source:** Deploy from branch `main` / folder `/docs`
- **Custom domain:** Optional (configure in Settings → Pages)

## Requirements

- [Quarto CLI](https://quarto.org/docs/get-started/installation.html) >= 1.3
- GitHub repository named `MarcelloZago.github.io`

## License

This website content is personal academic material.
