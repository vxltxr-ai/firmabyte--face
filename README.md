# vxltxr llc — Landing Page

A lightweight, static landing page for vxltxr llc. No build step required.

## Structure

```
index.html          — Main page (shell + loader)
style.css           — Styles
partials/
  body.html         — Main body content (edit this)
  footer.html       — Footer content (edit this)
assets/
  logo.png          — Company logo
  favicon.ico       — Browser tab icon
```

## Editing Content

Edit `partials/body.html` and `partials/footer.html` directly — they are loaded into `index.html` at runtime via a small JS script.

## Local Development

Open `index.html` in your browser (or use a local server for fetch to work):

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Push to GitHub and enable GitHub Pages (Settings → Pages → Source: main branch).

For a custom domain, add a `CNAME` file at the repo root with your domain name.
