# Venkatesh Patte — Portfolio

Personal portfolio site. Static HTML/CSS/JS, no build step, no dependencies beyond Google Fonts.

## Structure

```
.
├── index.html          # all page content
├── styles.css           # all styling (edit colors in :root at the top)
├── script.js             # small enhancements (mobile nav, scroll reveal)
├── assets/
│   ├── profile.jpg       # hero photo
│   └── avatar.jpg        # small square avatar used in the nav bar
└── README.md
```

## Customize

- **Colors** — open `styles.css`, edit the CSS variables at the top of `:root` (`--amber`, `--teal`, `--pink`, `--deep`, etc). Everything else references these.
- **Text** — all copy lives directly in `index.html`, edited section by section (About, Skills, Experience, Work, Contact).
- **Links** — search `index.html` for `yourusername` and `#` to find the LinkedIn, GitHub, and project links that still need filling in.
- **Photo** — swap `assets/profile.jpg` and `assets/avatar.jpg` for new images at roughly the same aspect ratio (profile ≈ 2:3 portrait, avatar 1:1 square).

## Run locally

Just open `index.html` in a browser — no server needed. Or, for live-reload while editing:

```
npx serve .
```

## Deploy on GitHub Pages

1. Push this folder to a repo (e.g. `yourusername.github.io` for a root site, or any repo name for a project site).
2. In the repo settings, enable **Pages** → deploy from the `main` branch, root folder.
3. If using a custom domain, add a `CNAME` file with your domain name at the repo root.
