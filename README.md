# guidona.github.io

My personal site: https://guidona.github.io/

A one-page portfolio and CV built with [Hugo](https://gohugo.io), no theme. Pushing to `master` rebuilds and
publishes it to GitHub Pages (`.github/workflows/hugo.yaml`).

- `data/cv.yaml`: all the content. Update the CV, projects, hero stats and photo here.
- `assets/images/`: the portrait and project images, resized by Hugo at build time.
- `layouts/`: the page (`home.html`) and its frame (`baseof.html`).
- `assets/css/main.css`: styles, including dark mode and a print layout (printing the page, or the
  "Print as CV" button, gives a compact CV without the photo and projects).
- `static/portfolio/`: redirects the site's old address, guidona.github.io/portfolio/.

Preview locally with `hugo server`.
