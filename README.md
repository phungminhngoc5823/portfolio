# Phùng Minh Ngọc — Product Marketing & AI Portfolio

Ready-to-publish static GitHub Pages repository. No build command is required.

## Files

- `index.html` — complete portfolio UI and application runtime
- `public/images/` — original portfolio image assets
- `public/images/marketing-lab/` — image assets extracted from the embedded Marketing Lab module
- `.nojekyll` — disables Jekyll processing on GitHub Pages

## Image-quality fix

Case-study evidence images use their intrinsic width and only shrink responsively when needed. They are no longer forced to fill a wider container, which prevents browser upscaling of lower-resolution screenshots. Hero and thumbnail treatments are unchanged.

## Deploy

1. Upload all files/folders in this package to the repository root.
2. GitHub Pages: **Deploy from a branch** → `main` → `/(root)`.
3. No npm/Vite/build step is needed.
