# jcec.hub - Static Multi-Page Website

Official static website for `jcec.hub`, a professional workspace in Gaza.

## Overview

This project is a lightweight, multi-page static website built with:

- HTML
- CSS
- Vanilla JavaScript

It includes:

- Arabic/English language toggle
- Responsive layout (mobile, tablet, desktop)
- Gallery lightbox
- WhatsApp quick actions
- SEO basics (`robots.txt`, `sitemap.xml`, metadata)

## Project Structure

```text
jcec.hub/
  about.html
  contact.html
  gallery.html
  hours.html
  index.html
  services.html
  robots.txt
  sitemap.xml
  assets/
    css/style.css
    js/main.js
    images/
```

## Run Locally

Because this is a static site, you can run it with any simple local server.

### Option 1: VS Code Live Server

1. Open the project in VS Code.
2. Right-click `index.html`.
3. Select `Open with Live Server`.

### Option 2: Python HTTP Server

```bash
python -m http.server 8080
```

Then open:

`http://localhost:8080`

## Deployment

### GitHub (Temporary)

1. Create a new repository on GitHub.
2. Add remote:

```bash
git remote add origin https://github.com/<USERNAME>/<REPO>.git
```

3. Push:

```bash
git branch -M main
git push -u origin main
```

### Netlify (Recommended for static hosting)

1. Connect your GitHub repository to Netlify.
2. Build command: *(leave empty)*.
3. Publish directory: `/` (root).
4. Deploy.

## Notes

- Main language defaults to Arabic.
- No backend is required.
- Keep images optimized for better performance.

## Developer

Designed and developed by **Yousif Ayman**  
YAD Services

