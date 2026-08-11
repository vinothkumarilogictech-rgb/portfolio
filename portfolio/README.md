# Vinothkumar J — Portfolio Website

A premium, dark, futuristic portfolio built with vanilla HTML5, CSS3 and JavaScript —
no frameworks, no build step. Just open `index.html` in a browser.

## Structure

```
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── profile.jpg      ← your uploaded photo (already in place)
│   └── resume.pdf        ← add your resume here (see below)
└── README.md
```

## Before you publish — a few things to finish

The following placeholders were used because real values weren't provided.
Search the files listed for the exact text to update:

1. **Resume file** — the "Download Resume" button links to `assets/resume.pdf`,
   which doesn't exist yet. Drop your resume PDF into `assets/` with that
   exact filename, or update the `href` in `index.html`.
2. **Social links** — GitHub and LinkedIn links currently point to `#`
   (three places: hero, contact section, footer). Replace with your real
   profile URLs, e.g. `https://github.com/yourusername`.
3. **Email address** — `hello@example.com` is a placeholder used in the
   contact section and footer (`mailto:` links). Replace with your real
   email address.
4. **Contact form** — the form currently validates on the frontend only and
   shows a success message; it doesn't send anywhere yet. To make it
   functional, connect it to a form backend (e.g. Formspree, EmailJS) or
   your own server endpoint inside `js/script.js`.

## Customizing

- **Colors** — all colors are CSS variables at the top of `css/style.css`
  under `:root` (`--accent-cyan`, `--accent-violet`, etc.).
- **Content** — all text lives directly in `index.html`, organized by
  section comments (`<!-- ============ HERO ============ -->` etc.).
- **Fonts** — Space Grotesk (headings), Inter (body), JetBrains Mono
  (labels/badges), loaded from Google Fonts.

## Browser support

Modern evergreen browsers (Chrome, Edge, Firefox, Safari). Uses CSS Grid,
`backdrop-filter`, and `IntersectionObserver`.
