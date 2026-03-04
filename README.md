# Nexora AI GitHub Pages Website

Static one-page landing site for **Nexora AI**.
No build step required.

## Files

- `index.html`
- `styles.css`
- `script.js`
- `sitemap.xml`
- `robots.txt`
- `humans.txt`

## Contact Form (Formspree)

The contact form submits to:

```html
action="https://formspree.io/f/mjgenygk"
```

This endpoint works on GitHub Pages with no backend.

## Placeholder Setup

1. Replace `REPLACE_WITH_SITE_URL` in:
   - `index.html` (canonical, Open Graph, Twitter, JSON-LD)
   - `sitemap.xml`
   - `robots.txt`
2. Replace `REPLACE_WITH_LINKEDIN_URL` in the JSON-LD `sameAs` field in `index.html`.

## Required Assets

Add these files under `/assets`:

- `/assets/og.png` (1200x630)
- `/assets/logo.png`
- `/assets/favicon.ico`
- `/assets/apple-touch-icon.png`

## Enable GitHub Pages

1. Push this repository to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/(root)`
5. Save and wait for deployment.

Your site URL will look like:
`https://<your-username>.github.io/<repo-name>/`

## SEO Checklist

1. Add your production URL in all SEO placeholders.
2. Verify your site in Google Search Console.
3. Submit `sitemap.xml` in Search Console.
4. Request indexing for the homepage.
5. Re-check crawl/index status after deployment updates.

## Important SEO Reality Note

SEO helps indexing and ranking, but ranking depends on competition, backlinks, and content.

## Quick Local Preview

```bash
cd /Users/mac/Documents/Nexora-AI
python3 -m http.server 8000
```

Open `http://localhost:8000`.
