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

## Best way to publish

Treat `Mo.fitness` as its own small GitHub repository.

Recommended flow:

1. Create a new GitHub repository named `Mo.fitness`.
2. Upload the full contents of this folder into that repository.
3. Go to `Settings` -> `Pages`.
4. Set the source to `GitHub Actions`.
5. Push to `main` or manually run the workflow from `Actions`.

Once Pages is enabled, GitHub will publish this folder as its own standalone site.

## Notes

- The page entry point is `index.html`.
- If you later want a custom domain, add a `CNAME` file here.
