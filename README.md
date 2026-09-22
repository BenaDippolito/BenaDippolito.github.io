# BenaDippolito.github.io

Personal portfolio site for Benjamin Dippolito, 21 year Army retiree and inspiring GRC Engineer.

## Built with

- Semantic HTML
- CSS with responsive layouts and reduced-motion support
- Small vanilla JavaScript module for the accessible mobile menu
- GitHub Pages for hosting

## Run locally

This is a static site and has no build step or package dependencies. From this directory, start any local static server available on your machine, for example:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser. Opening `index.html` directly also works, but a local server is closer to the GitHub Pages environment.

## Updating the site

- Personal introduction and profile copy live in `index.html`.
- Project cards are in the `project-grid` section of `index.html`. Replace roadmap entries with completed projects only when source links, descriptions, and technologies are verified.
- Skill groups and social links are also maintained in `index.html`.
- Replace or add images in the repository and include descriptive `alt` text for every meaningful image. The current design does not require image assets.
- Visual styling and responsive behavior are in `styles.css`.
- Mobile navigation behavior is in `script.js`.

## Change log requirement

Whenever a file in the `BenaDippolito.github.io` folder is added, edited, or removed, update this README in the same change. Add a concise entry to the change log below describing what changed and why. Keep the entry factual and include the affected filename when useful.

## Change log

### 2026-09-22

- Added the responsive portfolio landing page and its supporting styles and mobile navigation in `index.html`, `styles.css`, and `script.js`.
- Added accessible footer links for GitHub and LinkedIn, including Font Awesome brand icons in `index.html`.
- Added site maintenance, local preview, editing, and GitHub Pages deployment instructions to this README.

## Deploy with GitHub Pages

1. Push the contents of this directory to the `main` branch of `BenaDippolito.github.io`.
2. In the repository, open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
4. GitHub Pages will publish the site at `https://benadippolito.github.io/` after the deployment completes.

There are currently no build, test, lint, or formatting commands configured for this static repository.
