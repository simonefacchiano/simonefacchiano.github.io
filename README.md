# Simone Facchiano Academic Website

Static personal academic website designed for GitHub Pages or Vercel.

## Structure

- `index.html`: main site markup
- `css/styles.css`: custom styling and hover effects
- `images/`: profile placeholder and future assets
- `profile-images/`: rotating hero photos
- `cv/`: CV PDF used by the site
- `projects/`: optional project assets/pages

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
```

## Profile Photos

The homepage profile gallery is configured in the script at the bottom of `index.html`.

## Deploy

### GitHub Pages

Push the folder contents to `simonefacchiano.github.io` and enable GitHub Pages from the repository root.

### Vercel

Import the repository into Vercel and deploy as a static site with the `website` folder as the root directory if needed.
