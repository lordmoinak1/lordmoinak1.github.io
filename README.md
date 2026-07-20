# lordmoinak1.github.io

Personal academic website of **Moinak Bhattacharya** — PhD candidate at Stony Brook University and visiting PhD student at Columbia University. Research in medical AI, medical imaging, foundation models, and neuro-oncology.

🔗 **Live:** https://lordmoinak1.github.io

## About

A single-page static site (no build step) ported from the original Google Sites page. Just plain `index.html` with embedded CSS/JS, served directly by GitHub Pages.

```
.
├── index.html          # the whole site
└── assets/
    └── img/
        └── profile.jpg  # profile photo
```

## Editing

Everything is in `index.html`:

- **Bio / titles** — the hero and About sections
- **News** — the `#news` section
- **Research** — the `#research` cards (each links to Google Scholar)
- **Activities** — the `#activities` panels (reviewer, achievements, service)
- **Contact / socials** — the `#contact` section

To preview locally, open `index.html` in a browser or run `python3 -m http.server` and visit `http://localhost:8000`.

## Deployment

GitHub Pages serves the `main` branch automatically. Push to `main` and the live site updates within a minute.
