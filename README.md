
Action: file_editor create /app/portfolio/README.md --file-text "# Farras — Portfolio (Neo-Brutalism, Static)

Pure HTML/CSS/JavaScript multi-page portfolio. Zero build step. Ready to deploy to GitHub Pages or Vercel.

## Structure

```
portfolio/
├── index.html            # Home / Hero
├── about.html            # About + manifesto chapters + timeline
├── skills.html           # Skills grid with progress bars
├── projects.html         # Project grid (3 projects)
├── project-detail.html   # Dynamic detail via ?id=1|2|3
├── contact.html          # Contact links + form
├── 404.html              # Not found
└── assets/
    ├── css/style.css     # Design system + all components
    ├── js/main.js        # Lenis + reveals + progress + nav + form
    └── images/           # (empty — visuals rendered as CSS typography)
```

## Features

- **Neo-Brutalism** aesthetic: thick borders, hard shadows, oversized display type, sticker rotations.
- **Lenis** smooth momentum scroll.
- **Custom cursor** (dot + ring, hover magnet).
- **On-load hero reveal**: line-by-line masked entrance.
- **IntersectionObserver** scroll reveals.
- **Progress bars** animate on scroll.
- **Marquee** editorial (skills strip).
- **Active nav highlight** based on current URL.
- **Hamburger** mobile menu with numbered items.
- **Back-to-top** floating button.
- **Contact form** with client-side validation.
- **Responsive** from 320px upward.

## Deploy

### GitHub Pages
1. Push contents of `/portfolio/` to a repo (root or `docs/`).
2. Repo → Settings → Pages → Source: `main` branch, folder `/` (or `/docs`).

### Vercel
1. `vercel` from within `/portfolio/` directory. No build step needed — it's static.

## Customize

- Colors: edit `--brand-*` and `--bg` variables in `assets/css/style.css`.
- Contacts: replace `hello@farras.dev`, WhatsApp, GitHub, LinkedIn, Instagram links in every HTML page (or use find-replace).
- Projects: edit the `projects` object in `project-detail.html` and the three cards in `projects.html` + `index.html`.
"
Observation: Create successful: /app/portfolio/README.md
