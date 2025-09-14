# Elite Rackz Website

A lightweight, professional marketing site for **Elite Rackz** with a Damotech-like aesthetic (clean, engineering-forward).

## Structure
- `index.html` — Landing page
- `products.html`, `services.html`, `about.html`, `contact.html`, `app.html`
- `assets/css/styles.css`, `assets/js/main.js`, `assets/images/*`

## Deploy on GitHub Pages
1. Create a new repo and upload all files from this folder.
2. In **Settings → Pages**, set **Branch** to `main` (root).
3. Your site will be available at `https://<your-user>.github.io/<repo>/`.

## Replace Images
Drop your photos into `assets/images/` and keep the same filenames to see them live immediately:
- `header-placeholder.jpg` (hero background)
- `product-collage-placeholder.jpg`
- `repair-kit-a.jpg`, `repair-kit-b.jpg`, `repair-kit-c.jpg`
- `end-aisle-guard.jpg`, `column-guard.jpg`, `wire-guard.jpg`
- `ceo-headshot-placeholder.jpg`
- `app-mockup-placeholder.jpg`
- `og-placeholder.jpg`
- `logo-mark.svg`, `favicon.svg`, `badge-engineered.svg`, `badge-lifetime.svg`, `badge-usa.svg`, `appstore-badge-placeholder.svg`

## Forms
Forms are configured with `data-netlify="true"` attributes for quick static hosting. 
If you prefer Formspree, replace the `<form>` `action` with your Formspree endpoint.

## Notes
- Tailwind is included via CDN for speed. For production builds with purge, set up a Tailwind pipeline later.
- Colors and typography can be adjusted in the Tailwind config in the HTML `<head>`.
