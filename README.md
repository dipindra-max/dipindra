# DY Static Website

This is a single-page, deployment-ready static portfolio for Dipindra Yadav (DY).

## Files
- `index.html` — complete website, CSS and JavaScript are included in one file.
- `assets/profile.png` — the profile photo supplied for this website.

## What works without a backend
- Responsive mobile/tablet/desktop layout
- Light/dark mode
- Sticky navigation and mobile menu
- Smooth section navigation
- Projects section with links
- Blog search and category filter
- Like counter stored in the visitor's browser
- Contact form opens the visitor's email app
- Social links
- SEO title/description and Open Graph basics
- No build process required

## Important
A static HTML site cannot securely provide PostgreSQL, admin login, real comments, server-side analytics, scheduled publishing, or server-stored contact messages. Those features require a backend. This package is intended as the clean visual/static version to deploy first.

## Render
Create a **Static Site** in Render:
- Build command: leave empty
- Publish directory: `.`
- Connect the GitHub repository containing these files.

## GitHub
Upload `index.html` and the `assets` folder to the repository root. Keep `assets/profile.png` exactly at that path.

## Custom domain
After the Render site is live, add your domain in Render's Custom Domains section and follow the DNS records Render provides.
