# Codebase map (onboarding 2026-07-08)

**Reallohnverlust-Rechner** — a single-page, client-side calculator for German
real-wage loss (nominal raise vs. inflation → real change). MIT-licensed.

## Layout
- `index.html` — the entire app: HTML + inline CSS + JS. No build step, no
  backend, no dependencies. Runs by opening the file / via GitHub Pages.
- `README.md` / `README.de.md` — description (keep in sync).

## Run / deploy
Open `index.html` in a browser, or serve statically (GitHub Pages). All
computation is in-page JavaScript; no network calls, no data collection.

## Conventions
- Self-contained single file — keep it dependency-free and offline-capable.
- German-facing UI; keep both READMEs in sync.
- No secrets, no backend.

## Notes
Validation = open in a browser and check the calculation. Trivial to port /
embed (pure HTML/JS).
