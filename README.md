# Strattega Portfolio Website

Minimal, fast, single-page portfolio for Strattega. Built to run on GitHub Pages with static files only.

## Publish on GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Save. Your site will be available at the URL GitHub shows.

## Preview locally
From the repo root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Edit points
- Main content: `index.html`
- Styles: `styles.css`
- Mobile menu: `scripts.js`
- Replace email and LinkedIn link in the Contact section of `index.html`.
- Update case study outcomes where placeholders appear: `[add metric]` and `[add result]`.

## File tree
- `index.html`
- `styles.css`
- `scripts.js`
- `assets/`
