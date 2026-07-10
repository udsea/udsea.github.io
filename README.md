# udsea.github.io

Personal website for Udbhav, built with the [`al-folio`](https://github.com/alshedivat/al-folio) Jekyll template.

## Site Settings

The main site configuration is in `_config.yml`.

Important values for this GitHub Pages user site:

```yml
url: https://udsea.github.io
baseurl:
```

Keep `baseurl` empty for the root `udsea.github.io` site.

## Content

- Homepage bio: `_pages/about.md`
- Publications: `_bibliography/papers.bib`
- Projects: `_projects/`
- Blog posts: `_posts/`
- Social links: `_data/socials.yml`
- Repository cards: `_data/repositories.yml`

## Deploy

The al-folio deployment workflow is `.github/workflows/deploy.yml`. It builds the Jekyll site and publishes `_site` to the `gh-pages` branch through GitHub Actions.

GitHub Pages should use:

- Source: deploy from a branch
- Branch: `gh-pages`

The workflow currently triggers on `main`, `master`, and `notmain`.
