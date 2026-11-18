# Chrono Vane — GitHub Pages Site

This is a lightweight, zero-dependency static site for Chrono Vane suitable for deployment on **GitHub Pages**.

## Structure

- `index.html` — Chrono Vane landing page (Hero, How it Works, Categories, Philosophy, FAQs, Download links).
- `privacy.html` — Full Privacy Policy page.
- `style.css` — Compiled Tailwind / UI stylesheet (includes dark theme styles, gradients, glass panels).
- `icon.svg`, `favicon.ico`, `apple-touch-icon.png`, `site.webmanifest`, etc. — All app logos and favicon assets.

## Deployment to GitHub Pages

1. Initialize a git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for GitHub Pages"
   ```
2. Create a GitHub repository (e.g. `chronovane` or `<user>.github.io`) and push:
   ```bash
   git remote add origin https://github.com/<username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
3. In GitHub Settings:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment**, set Source to **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`.
   - Save. Your site will be live immediately.
