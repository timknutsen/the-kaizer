# The Kaizer - GitHub Pages Site

Simple static band page for **The Kaizer**.

## Publish to GitHub Pages

1. Create a new repository on GitHub (for example: `the-kaizer`).
2. In this folder, run:

```bash
git init
git add .
git commit -m "Create The Kaizer GitHub Pages site"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPO>.git
git push -u origin main
```

3. On GitHub, go to `Settings -> Pages`.
4. Under `Build and deployment`, set:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
5. Save, then wait about 1-2 minutes.
6. Your site will be live at:

`https://<YOUR_GITHUB_USERNAME>.github.io/<YOUR_REPO>/`

## Local preview

Open `index.html` directly in a browser.
