# portfolio

My personal site: https://guidona.github.io/portfolio/

A one-page CV built with [Hugo](https://gohugo.io), no theme. Pushing to `master` rebuilds and
publishes it to GitHub Pages (`.github/workflows/hugo.yaml`).

- `data/cv.yaml`: all the content. Update the CV here.
- `layouts/`: the page (`home.html`) and its frame (`baseof.html`).
- `assets/css/main.css`: styles, including dark mode and a print layout (printing the page gives a
  compact CV).

Preview locally with `hugo server`.
