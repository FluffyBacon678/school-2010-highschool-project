# Learning Disabilities — Information Site (2010 redesign)

A modern, responsive redesign of a high-school web project from 2010 about
learning disabilities. The original was an ASP.NET site with inline styles and
a fixed 960px layout; this version is a clean, dependency-free static site.

## Topics covered

- **ADHD** — attention deficit hyperactivity disorder
- **Dyslexia** — reading difficulties
- **Dysgraphia** — writing difficulties
- **Dyscalculia** — arithmetic difficulties

All content is in Hebrew (right-to-left).

## Features

- Pure HTML + CSS, no build step and no server-side dependencies
- Fully responsive (mobile, tablet, desktop)
- Sticky navigation with active-state highlighting
- Color-coded sections per topic
- Image gallery with a lightbox
- Resources/links page

## Running locally

Any static file server works, for example:

```bash
python3 -m http.server 4200
```

Then open <http://localhost:4200>.

## Deployment

Hosted on GitHub Pages (deploy from the `main` branch, root folder).
GitHub rebuilds and republishes automatically on every push to `main`.
