# Personal Website

Clean single-page portfolio site for Akshat Singh, designed to present work in hardware, inference systems, machine learning, and systems-focused engineering.

## Live Site

Expected GitHub Pages URL:

`https://akshx-at.github.io/personal-website/`

If GitHub Pages has not been enabled yet, pushing to `main` will trigger the deployment workflow included in this repository. In some cases, GitHub may require one manual step in the repository settings to confirm that Pages should deploy from GitHub Actions.

## What This Site Includes

- concise hero section with current focus areas
- about section describing technical interests and background
- featured project cards linked to GitHub repositories
- contact section with LinkedIn and GitHub

## Design Direction

The site is intentionally:

- simple and clean
- warm and understated rather than template-like
- slightly hardware-inspired through grid treatments and mono accents
- lightweight, with no framework or build step required

## Stack

- HTML
- CSS
- vanilla JavaScript
- GitHub Pages for deployment

## Repository Structure

```text
personal-website/
├── .github/workflows/deploy.yml  # GitHub Pages deployment workflow
├── index.html                    # Site structure and content
├── styles.css                    # Visual system and layout
├── script.js                     # Small reveal-on-scroll behavior
└── README.md
```

## Local Preview

Open `index.html` directly in a browser, or run a quick static server:

```bash
cd personal-website
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating Content

The easiest content changes are all in `index.html`:

- hero copy
- work experience line
- about paragraph
- project cards
- external links

Visual changes live in `styles.css`.

## Deployment

This repository includes a GitHub Actions workflow that deploys the site to GitHub Pages whenever `main` is updated.

Workflow file:

`/.github/workflows/deploy.yml`

## Notes

- The current experience line was written from public profile context and can be refined at any time.
- The JavaScript is intentionally minimal and only powers section reveal motion.
- This site is easy to extend later with a resume link, writing section, custom domain, or more detailed project pages.
- GitHub Pages deployment was configured to use GitHub Actions for publishing.
