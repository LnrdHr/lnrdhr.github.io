# Leonard Jedvaj — GitHub Pages portfolio

A static HTML/CSS/JavaScript site, with editable project data in `projects.json`.

## Structure

```
index.html         Main page structure
style.css          Appearance and responsive styling
script.js          Project rendering, navigation and image viewer
projects.json      Editable project descriptions, links, galleries and diagrams
images/            Project photos and oscilloscope captures
README.md          These instructions
```

## Edit a project

Open `projects.json`, locate the project's `id`, and edit `title`, `summary`, `description`, `details`, `links`, `diagram`, or `gallery`. Keep valid JSON (double-quoted strings, commas between entries, no trailing commas).

## Add a project

Add another object to the `projects` array, for example:

```json
{
  "id": "new-project",
  "layout": "card",
  "eyebrow": "Personal project",
  "title": "New Project",
  "summary": "What this project does.",
  "description": "How the project works and what engineering decision you made.",
  "visual": {
    "type": "image",
    "src": "images/new-project.jpg",
    "alt": "New project screenshot"
  },
  "links": [
    {"label": "Repository ↗", "url": "https://github.com/LnrdHr/example"}
  ]
}
```

Add the image inside `images/`. Omit `visual` if you don't have a screenshot. The layout can be `feature`, `card`, or `compact`.

## Publish

The repository's GitHub Pages deployment should use `main` / `(root)`. Merge the portfolio organization pull request when ready. Future project edits usually require changing only `projects.json`.

## Preview locally

Run `python3 -m http.server 8000` in the repository directory and open http://localhost:8000/. Opening `index.html` directly as a local file may not load the JSON because the site uses `fetch()`.

## Privacy

On GitHub Free, keep the Pages repository public. Do not publish credentials, internal URLs or private client information. The website and its JSON file are publicly accessible.
