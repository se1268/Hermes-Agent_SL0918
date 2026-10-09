# Todo List — single-file web app

A modern, dependency-free Todo app in one HTML file (HTML + CSS + vanilla JS).
Tasks, done-state, and filters persist in your browser via `localStorage`.

## Features
- Add / delete / mark done or not done
- Filter: All · Pending · Done, plus "Clear completed"
- Persists in `localStorage` (survives reloads, syncs across tabs)
- Dark mode by default, auto light mode via `prefers-color-scheme`
- Keyboard accessible (Enter/Space on checkboxes), responsive

## Local use
Open `index.html` in any browser. No build step, no dependencies.

## Online
Deployed via the GitHub Pages auto-build workflow
(`.github/workflows/deploy-pages.yml`) — runs on every push to `main`.