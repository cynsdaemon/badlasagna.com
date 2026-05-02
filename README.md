# Bad Lasagna Comic

This is the repo for **Bad Lasagna**, cozy‑weird comic about cosmic bureaucracy, emotional labor, and the daemons who run it. This project is live at [badlasagna.com](https://badlasagna.com). 

The repo is a lightweight, static webcomic site built with HTML, CSS, and vanilla JavaScript, hosted on GitHub Pages. The site is intentionally minimal, fast, and easy to maintain — no frameworks, no build tools, no databases.

All comic episodes, navigation, and archive pages are powered by a single JSON file, making updates simple and scalable.

## Tech Used

### Frontend
HTML5 — static pages for the site structure

CSS3 — custom theme, responsive layout, character cards, buttons

JavaScript (vanilla) — loads comic data, handles navigation, builds archive page

Google Fonts — ABeeZee (body) + Coiny (logo/headers)

### Hosting
GitHub Pages — free static hosting

No server, no backend, no build pipeline

### Data
archive.json — the single source of truth for all comic episodes

Stores:

- episode number

- title

- intro text

**TODO:** - future metadata like tags or thumbnails

### Images
Comic pages stored as .jpg in /archive/comics/

Character icons stored in /img/

Placeholder icons auto‑generate initials if no image is provided

For **feedback** and suggestions, feel free to [open an issue on Github](https://github.com/cynsdaemon/badlasagna.com/issues) for this project. This project is built with love :heart: coffee :coffee: and an awesome playlist :musical_note:. Copyright &copy; 2025 - Today.
