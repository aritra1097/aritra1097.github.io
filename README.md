# Aritra Basu

This is the source for my [personal website](https://aritrabasu.net/), where I share my research, teaching, CV, and a little about life outside work.

The site is built with plain HTML and CSS. You can download it and open `index.html` in a browser to look around. There is nothing to install.

## Trying a different look

If you have an idea for the colors or design, feel free to fork this repository and try it out. Most of the styling is in `assets/style.css`; the main colors are defined at the top of that file.

Screenshots or a link to your version would be great for comparing ideas. You can also open a pull request so I can see the changes and try them locally. Changes in a fork stay separate from my live site until I choose to bring them over.

## Finding your way around

- `index.html` — home page
- `research.html` — papers and research summaries
- `teaching.html` — courses and teaching interests
- `cv.html` — education, experience, and a link to my CV
- `beyond-research.html` — a few things outside research
- `assets/` — stylesheet, photographs, favicon, and PDF copies

The CV and job market paper buttons link to Google Drive. The copies in `assets/` are kept separately.

For a local preview that also handles the 404 page correctly, run this from the site folder if you have Python installed:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit [localhost:8765](http://localhost:8765).

The site is hosted on GitHub Pages. Updates pushed to `main` are published to the live website.
