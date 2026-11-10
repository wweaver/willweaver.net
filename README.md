# willweaver.net

Personal site for Will Weaver. Plain HTML and CSS with no build step.

## Files

- `index.html` – the page
- `styles.css` – all styles, with light and dark themes
- `fonts/` – self-hosted Schibsted Grotesk (SIL Open Font License, see `fonts/OFL.txt`)
- `resume.pdf` – linked from the page
- `favicon.svg` and `apple-touch-icon.png` – browser and home-screen icons
- `og-image.png` – link preview image (1200×630) for LinkedIn, Slack and texts
- `404.html` – served by Vercel for missing pages

## Run locally

Paths are root-relative, so serve the folder instead of opening the file directly:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Works as-is on Vercel, Cloudflare Pages, Netlify or GitHub Pages. On Vercel, import the repo with the "Other" framework preset, no build command and the root directory as output.
