# Stephanie P. Hao

This is a lightweight static website for GitHub Pages.

## Files

- `index.html` — homepage
- `design-den.html` — Design Den page
- `3-minute-thesis.html` — 3MT page
- `styles.css` — site styling

## How to publish on GitHub Pages

1. Create a new GitHub repository, for example:
   `sphao.github.io`

2. Upload all files in this folder to the repository.

3. Go to:
   Settings → Pages

4. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root

5. Save.

Your site should appear at:
`https://sphao.github.io/`

## Google Search Console

After the site is live:

1. Go to Google Search Console.
2. Add a URL-prefix property:
   `https://sphao.github.io/`
3. Choose the HTML tag verification method.
4. Paste the meta tag into the `<head>` section of each HTML file, replacing the placeholder comment.
5. Commit the changes.
6. Click Verify.
7. Use URL Inspection and request indexing for:
   - `https://sphao.github.io/`
   - `https://sphao.github.io/design-den.html`
