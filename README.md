# Collins Wandji — Portfolio

Static portfolio website. The GitHub profile README lives on `main`. This branch is the site.

## Run locally

From the repository root:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080

`index.html` can also be opened directly. Theme preference is stored in the browser.

## Update the site

- Page copy is in `index.html`.
- Visual styles and both themes are in `css/style.css`.
- Theme toggle and the mobile menu are in `js/main.js`.
- The public resume is `resume/resume.pdf`. Replace that file when the resume changes. Do not edit the PDF in place unless you mean to publish a new one.

## Deploy

Pushes to `dev` run `.github/workflows/deploy.yml`, which publishes the branch with GitHub Pages. The site is served from `https://wandji69.github.io/Wandji69/`.

In the repository settings, GitHub Pages needs to use **GitHub Actions** as the source. `main` stays the profile README and is not the Pages source.
