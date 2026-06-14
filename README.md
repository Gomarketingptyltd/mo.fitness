# Mo.fitness

Single-file landing page for a fitness coach brand.

## What is inside

- `index.html`: self-contained public page
- `.nojekyll`: tells GitHub Pages not to run Jekyll processing
- `.github/workflows/deploy-pages.yml`: GitHub Pages deployment workflow

## Replace the placeholders

Search for `{{` inside `index.html` and replace each placeholder with your real:

- coach name
- programs
- pricing
- testimonials
- contact details

## Publishing

This repo is set up to deploy through GitHub Pages with GitHub Actions.

Recommended flow:

1. Keep the page files at the repository root.
2. Push changes to `main`.
3. Go to `Settings` -> `Pages`.
4. Set the source to `GitHub Actions` if it is not already selected.

After the first successful workflow run, GitHub will publish this page as its own standalone site.

## Notes

- The page entry point is `index.html`.
- If you later want a custom domain, add a `CNAME` file here.
