# Portfolio Website

A modern, responsive single-page portfolio built with plain HTML, CSS, and JavaScript — no frameworks, no build step.

## Preview

Open `index.html` directly in your browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
.
├── index.html   # Markup and content
├── styles.css   # Design system, layout, responsive rules
├── script.js    # Nav state, mobile menu, scroll-reveal
└── README.md
```

## Customize

- **Name, bio, projects**: edit `index.html`. Each section is clearly commented.
- **Colors & fonts**: CSS variables at the top of `styles.css` (`--accent`, `--bg`, etc.).
- **Contact links**: update `mailto:` and socials in the `#contact` section.
- **Projects**: duplicate a `<article class="project">` block and swap in your own copy.

## Features

- Responsive, mobile-first layout (down to 480px)
- Dark theme with gradient accents and subtle grid background
- Sticky glassmorphism nav with mobile drawer
- Scroll-reveal animations (respects `prefers-reduced-motion`)
- Zero dependencies, zero build tools

## Deploy

Works on any static host:

- **GitHub Pages**: push and enable Pages on `main`.
- **Netlify / Vercel / Cloudflare Pages**: drop the folder in — no config needed.
