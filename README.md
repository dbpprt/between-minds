# Between Minds Project

A Hugo site for Shammi Bappert's Between Minds Project.

Production URL: `https://betweenmindsproject.com/`

## Development

Prerequisite: Hugo Extended `0.165.0` (the version used by CI).

```bash
make dev
```

This runs Hugo with `--disableFastRender`, which avoids the incremental render crash that can happen on this project when editing content-heavy pages such as `upcoming-book.md`.

Open the local preview at `http://localhost:1313/`.

## Production build

```bash
hugo
```

The generated site is written to `public/`.

## GitHub Pages

This repository deploys automatically to GitHub Pages through the workflow in `.github/workflows/hugo-pages.yml`.
