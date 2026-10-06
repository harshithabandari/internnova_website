# InternNova Homepage Redesign

A responsive, static homepage redesign for InternNova, based on the official site at [internnova.co.in](https://internnova.co.in/).

## Reference Notes

The existing homepage promotes virtual internships, pro tracks, courses, events, and student resources. The redesign brings those offerings into one clear browsing path, surfaces internship domains earlier, and makes the six-week format, mentorship, project work, and certificate details easier to scan. The existing brand line, "Build real skills. Land real jobs.", and the reference site's published student and program figures are retained.

The page uses the reference's published program details and verified 4.6/5 rating (309+ student reviews). It does not invent student testimonials.

## Preview

Open `index.html` in a browser. No build step or package installation is required.

## Publish

This is a static site. The repository includes a GitHub Actions workflow that deploys it to GitHub Pages on pushes to `main`.

Before the first deployment, a repository owner must open **Settings > Pages** and set **Build and deployment > Source** to **GitHub Actions**. Then rerun the failed **Deploy website to GitHub Pages** workflow from the repository's **Actions** tab. Later pushes to `main` deploy automatically.

The photos and web fonts are loaded from external providers and require an internet connection.

## Files

- `index.html` contains the page content and section structure.
- `styles.css` contains the responsive layout, colors, and animations.
- `script.js` handles the mobile navigation, reveal effects, and current year.