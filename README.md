# Aritra Basu — Academic website

Personal academic website: https://aritra1097.github.io/

Plain HTML and CSS; no build step, dependencies, tracking, or external fonts.

## Updating the site

- `index.html`: introduction, job market status, and contact details.
- `research.html`: papers and research summaries.
- `teaching.html`: teaching introduction, courses, and interests.
- `cv.html`: education and research experience.
- `assets/style.css`: shared design and responsive layouts.

CV and job market paper links point to PDFs in UMass Google Drive. Use Drive’s **Manage versions → Upload new version** to replace either PDF while preserving its URL. Copies are also kept in `assets/`.

GitHub Pages serves the repository root on `main`. Pushing changes to `main` updates the website.

Preview locally: `python3 -m http.server 8765 --bind 127.0.0.1`
