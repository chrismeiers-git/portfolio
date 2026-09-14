# Chris Meiers, PhD — Portfolio

Static HTML portfolio for GitHub Pages. Built from the career management
system in `Career & Job Search/career/07_portfolio` (roles_history.md,
achievements_inventory.md, voice_and_style_guide.md).

## Structure

- `index.html` — the portfolio page (hero, capabilities, four case studies,
  how-I-work, education, contact). Single-file HTML/CSS/JS, light/dark theme
  toggle, no build step.
- `samples/` — seven standalone "illustrative work sample" pages linked from
  each case study (fictional institution "Roselawn University," fictional
  data), styled to match the main page and its theme.
- `documents/` — the real KCKCC Strategic Enrollment Management Plan PDF
  referenced by two case studies. Two unused WSUTC PDFs are also here,
  no longer linked from the site.
- `Portfolio_Outline.md` — running content/design log: section-by-section
  outline, decisions made each edit pass, and open items to confirm before
  sending the site externally.

## Publishing

Plain static HTML — no build step. For GitHub Pages: Settings → Pages →
Deploy from a branch → `main` / `/ (root)`.

## Editing

See `Portfolio_Outline.md` for the current content outline and open items.
