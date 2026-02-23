HTML & CSS — Personal Collection

A small collection of static HTML, CSS and JavaScript examples, experiments and mini-projects. This repository contains a portfolio page, small games, SVG/CSS demos, forms, and other front-end learning experiments.

Table of Contents
- Project overview
- Folder-by-folder summary
- Notable files
- How to view locally
- Development tips & caveats
- Contributing, credits & suggested license
- Changelog

Project overview
This repository is a personal playground for front-end experiments and small static sites. Files are plain HTML/CSS/JS and are intended to be opened in a browser or served from a simple static server.

Folder-by-folder summary
- `CSS/` — Standalone pages demonstrating CSS and SVG examples.
  - Examples: `CSS/booknest.html`, `CSS/ridethewaves.html`.
  - Subfolder `CSS/2026.html/` contains `2026.html`, `0202020.html` and a media file `baile-rave.mp3` used by that example.
- `HTML/` — Several grouped examples and small sub-projects.
  - `HTML/Dynamic Site/` — `index.html`, `script.js`, `style.css` (canvas/dynamic demo).
  - `HTML/Coffee/` — `coffee.html`, `coffee-website.html` (small demo pages).
  - `HTML/Form/` — `form.html`, `studentregistration.html` (form examples).
  - `HTML/Nursing/` — `index.html`, `style.css` (sample layout/style).
  - `HTML/Random/` — assorted example pages and styles (many small demos).
  - Note: there is a folder named `website ` (with a trailing space) under `HTML/` — consider renaming to `website` to avoid path problems.
- `INDEX/` — Small demonstrations and index pages (`index.html`, `image.html`, `float.html`, etc.).
- `Mini Project - Sliding puzzle/` — Playable sliding puzzle game.
  - Files: `index.html`, `game.js`, `style.css`, `bg.mp3`.
- `PORTFOLIO/` — Portfolio single-page site (`PORTFOLIO/index.html`).

Notable files
- `PORTFOLIO/index.html` — The portfolio landing page (single-file site with embedded styles).
- `Mini Project - Sliding puzzle/index.html` — Playable sliding puzzle that uses `game.js` and `bg.mp3`.
- `HTML/Dynamic Site/index.html` — Dynamic/canvas demo that uses `script.js`.
- `CSS/2026.html/2026.html` — Example page with accompanying `baile-rave.mp3`.
- `INDEX/index.html` — Simple CSS text-styling demo.

How to view locally
Most pages can be opened directly by double-clicking the HTML file. For a more consistent experience (and to avoid cross-origin or media loading issues), serve the repository with a lightweight local server.

Recommended ways to serve the files:

1) Python 3 (built-in)

```bash
cd "HTML & CSS"
python3 -m http.server 8000
# open http://localhost:8000/ in your browser
```

2) VS Code — Live Server

- Open the folder in VS Code and use the Live Server extension to serve pages with live reload.

3) Node (npm)

```bash
cd "HTML & CSS"
npx serve .
# or install `serve` globally: npm i -g serve
```

Development tips & caveats
- Watch out for the repository root name: it contains an ampersand and space ("HTML & CSS"). Use quotes when changing directories: `cd "HTML & CSS"`.
- The folder `HTML/website ` has a trailing space in its name — this can cause confusion in shells and when linking; consider renaming it to `website`.
- Some demos reference audio or other media files; if you move pages between folders, update the relative paths accordingly.
- Use browser DevTools (F12) to debug console errors, network requests and styling problems.
- Keep each demo self-contained when possible: prefer an `index.html`, `style.css` and `script.js` per demo folder for clarity.

Contributing, credits & suggested license
- Contributions: small PRs are welcome (typo fixes, renaming folders to avoid trailing spaces, improved accessibility, new demos). For larger changes, please open an issue first.
- Author: Yuvraj Mishra (update as desired).
- Suggested license: MIT. If you accept MIT, add a `LICENSE` file to the repo with the MIT text. If you prefer another license (Apache-2.0, GPL, etc.), replace accordingly.

Changelog (template)
- Unreleased
  - YYYY-MM-DD — vNext — short description of changes
- 2026-02-23 — v0.1 — Initial README created describing repository contents

Next steps I can help with
- Add a LICENSE file (MIT default) and a `CONTRIBUTING.md` template.
- Rename the `website ` folder to remove the trailing space (I can do this if you want).
- Generate a brief `index` landing page that links to each demo for easier browsing.

If you'd like any of those, tell me which and I'll add them.
