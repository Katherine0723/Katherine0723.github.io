# Katherine0723.github.io

GitHub Pages user site. Pages serves the `main` branch at https://katherine0723.github.io/. Its pages only forward visitors to the personal website at https://katherine0723.github.io/aixinli/, which is built from the `aixinli` repository.

- `index.html` and `path.html` forward to the same page under `/aixinli/`.
- `404.html` forwards any other path to `/aixinli/` plus that path.

## Preview locally

    python3 -m http.server 8000

Then open http://localhost:8000/. The forward target `/aixinli/` exists only on the live site, so locally it ends on the server's 404 page.

## Checks

CI runs HTML validation (html-validate, standard preset) on pushes to `main` and on pull requests.
