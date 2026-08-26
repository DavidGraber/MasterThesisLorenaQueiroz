# Lorena Queiroz website

This is a Quarto website with four pages:

- Introduction
- Track Module 1
- Track Module 2
- Master Thesis

## Local preview

Install [Quarto](https://quarto.org/docs/get-started/) and run:

```sh
quarto preview
```

The generated files are written to `_site/`.

## GitHub Pages

The workflow in `.github/workflows/publish.yml` renders the site and publishes it with GitHub Pages. In the repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions**, then push to `main`.

Edit the `.qmd` files to add your content.
