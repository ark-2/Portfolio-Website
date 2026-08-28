# Austin Kerr — Portfolio

Personal portfolio site: home page, resume/CV, and project write-ups (consulting/analytics case studies plus a coding project).

**Live site:** _add your GitHub Pages / hosting URL here once deployed_

## Pages

| File | Description |
|---|---|
| `index.html` | Home page — intro, work-history timeline, project highlights |
| `cv.html` | Full resume timeline with role details and a downloadable PDF |
| `projects.html` | Detailed write-ups and slide decks for each project |
| `austin-kerr-resume.pdf` | Downloadable resume, linked from the CV page |

## Tech

Plain HTML, CSS, and JavaScript — no framework, no build step, no dependencies. Each page is fully self-contained: styles and scripts are embedded directly in the HTML, and all images are embedded as inline base64 data. This makes the site trivial to host anywhere that serves static files.

## Running locally

No build step needed. Either:

- Open `index.html` directly in a browser, or
- Serve the folder locally for a closer-to-production experience:
  ```bash
  python3 -m http.server 8000
  ```
  then visit `http://localhost:8000`

## Deployment

This site is deployed as a static site (see below for GitHub Pages steps). Because every page uses relative links (`cv.html`, `projects.html`, `index.html`), it works correctly whether hosted at a domain root or in a subpath like `username.github.io/repo-name/`.

## Updating content

Edits are made directly in the HTML files — there's no separate content source. Open the relevant page, find the section, and edit the markup/text in place.

---

© 2026 Austin Kerr
