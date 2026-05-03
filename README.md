# Personal website

Static site — no build step. Open `index.html` in a browser to preview locally,
or run `python3 -m http.server` from this directory.

## Files

- `index.html` — About page
- `papers.html` — Papers / publications
- `style.css` — Shared styles (light + dark mode)
- `resume.tex` — LaTeX source for the resume

## Deploy to GitHub Pages

1. Create a public repo named `<your-github-username>.github.io`.
2. Push these files to the `main` branch.
3. Visit `https://<your-github-username>.github.io/`.

For a custom domain (e.g. `nickmcgreivy.com`), add a `CNAME` file with the
domain name and configure DNS per GitHub's instructions.
