# hngaston.github.io

Personal website for Henry Gaston

Live at **https://hngaston.github.io**

## Structure

```
index.html            All page content (bio + links)
assets/css/style.css  Styling — minimal/academic, auto light & dark mode
assets/img/           Profile photo (headshot.jpg + headshot@2x.jpg for retina)
.github/workflows/    deploy.yml — publishes static files to the gh-pages branch on push to main
.nojekyll             Tells GitHub Pages to serve files as-is (no Jekyll build)
```

## Editing

- **Bio / text:** edit `index.html`.
- **Look & feel:** edit `assets/css/style.css` (colors live in the `:root` and dark-mode blocks at the top).
- **Photo:** replace `assets/img/headshot.jpg` (900w) and `headshot@2x.jpg` (1400w), keeping the same
  names, and update the `<img>` `width`/`height` in `index.html` to match.
- **Add publications/projects later:** uncomment the scaffolded `<section>` blocks near the
  bottom of `index.html` — the styling is already written.