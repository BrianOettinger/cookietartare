# Cookie Tartare

A premium raw cookie dough landing page built for GitHub Pages.

## Local setup

1. Open the project folder.
2. Preview `index.html` in your browser.

## GitHub setup

1. Create a new repository on GitHub named `cookietartare` (or any other name).
2. Add the remote:

   ```powershell
   git remote add origin https://github.com/<your-username>/cookietartare.git
   git branch -M main
   git push -u origin main
   ```

3. In GitHub, enable Pages for the repository:
   - Settings -> Pages -> Source -> `main` branch / `root`
   - Save and wait a few minutes for the site to publish.

## Custom domain

This project includes a `CNAME` file for `cookietartare.com`.

To use it:

1. Add these DNS records for `cookietartare.com`:
   - `A` -> `185.199.108.153`
   - `A` -> `185.199.109.153`
   - `A` -> `185.199.110.153`
   - `A` -> `185.199.111.153`

2. If you want `www.cookietartare.com`, add a `CNAME` record:
   - `www` -> `cookietartare.github.io`

3. In GitHub Pages settings, set the custom domain to `cookietartare.com`.

## Notes

- The site is a static HTML/CSS landing page.
- You can expand it with more pages, recipes, and shop links.
