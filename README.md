# Rudrakshi Patel — Portfolio

A minimal, single-page portfolio in one self-contained `index.html`. It has no build step and no dependencies apart from Google Fonts.

**Projects featured:** Hastakala (SIH 2026, Flutter), DocRiddles (Next.js + Supabase), Chirpy (iOS puzzle alarm), Contractions (iOS labor timer) and C Programming (110 programs).

## Preview locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Publish with GitHub Pages

1. Merge this branch into `main`.
2. Go to **Settings → Pages → Build and deployment** and choose *Deploy from a branch*, then `main` / `(root)`.
3. The site goes live at `https://rudrakshipatel.github.io/Rudrakshi-Patel/`.

## Editing

- Each project is an `<article class="project">` block. Copy one to add a new project.
- Colors live in the `:root` variables at the top of the file. Dark mode follows the system setting.
- To change the contact email, edit the `mailto:` link in the `#contact` section.
