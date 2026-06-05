# Sota Inoue Personal Academic Website

Bilingual personal academic website for PhD applications and research identity.

## Tech Stack

- Hugo
- Congo theme
- GitHub Pages

## Requirements

- Hugo `0.162.1` or compatible

## Local Development

```sh
hugo server -D
```

## Production Build

```sh
hugo --gc --minify
```

## Content Structure

- `content/en/` English pages
- `content/ja/` Japanese pages

## Static Assets

- `static/images/` images
- `static/cv/` CV files

## Theme

Congo is currently vendored under `themes/congo/`. This keeps the site buildable without requiring Git submodules or Hugo Modules.

The theme setup may later be converted to a Git submodule or Hugo Module for easier updates.
