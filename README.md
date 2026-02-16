# Andres Felipe Posada Moreno - Personal Academic Website

Personal academic website built with [Quarto](https://quarto.org/) and deployed on [GitHub Pages](https://andresfp14.github.io/).

## Prerequisites

- [Quarto CLI](https://quarto.org/docs/get-started/) (>= 1.6)
- [uv](https://docs.astral.sh/uv/) (Python package manager)

## Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/andresfp14/andresfp14.github.io.git
cd andresfp14.github.io
uv venv
uv sync --no-install-project
```

## Preview Locally

```bash
uv run quarto preview
```

This starts a local development server (typically at `http://localhost:4848`) with live reload.

## Build

```bash
uv run quarto render
```

The rendered site is output to the `_site/` directory.

## Deploy

Deployment happens automatically via GitHub Actions on push to `main`. The workflow:

1. Installs uv and Python
2. Installs project dependencies
3. Installs Quarto
4. Renders the site
5. Deploys to GitHub Pages

> **Note**: Ensure GitHub Pages is configured to use **GitHub Actions** as the source in your repository settings (Settings > Pages > Source > GitHub Actions).

## Project Structure

```text
.
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Homepage (About/Bio)
├── experience.qmd       # Experience timeline
├── publications/         # Individual publication pages + listing
├── projects/             # Project pages with images
├── blog/                 # Blog listing (empty, ready for posts)
├── contact.qmd           # Contact information
├── assets/               # Images, icons, resume PDF
├── styles/               # Custom SCSS
├── .github/workflows/    # GitHub Actions deployment
├── pyproject.toml        # Python dependencies (for uv)
└── CONTENT_INVENTORY.md  # Full content reference from Hugo migration
```

## License

Content: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
