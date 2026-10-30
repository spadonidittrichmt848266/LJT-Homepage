# LJT-Homepage

Personal academic homepage of Junteng Liu, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Pages

- **About** (`/`): biography, academic background, research experience, skills, publications, and contact information.
- **Publications** (`/publications/`): publication list.

## Site configuration

Site-wide settings and contact links are in `_config.yml`; the header links are in `_data/navigation.yml`. Publication entries are Markdown files in `_publications/`.

## Publishing

`.github/workflows/jekyll.yml` builds the site with Jekyll and deploys it to GitHub Pages on pushes to `master`. GitHub Pages must be enabled for this repository with **GitHub Actions** as the build/deployment source (Settings → Pages); the workflow requests this enablement automatically when the repository permissions allow it.
