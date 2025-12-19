# bells-shells.github.io

This repo is a GitHub Pages site using the Minimal Mistakes remote theme.

How to edit:
- Update `index.md` for the single-page content (markdown).
- Add images to `assets/images/` and reference them as `/assets/images/<filename>`.

Deployment:
- The root `index.html` currently redirects to `/home` which is generated from `index.md`.
- Push to your default branch (usually `main`).
- In the repository Settings → Pages, ensure the site is built from the default branch / root.
- After pushing, the site will be visible at: `https://<your-username>.github.io/` (may take a minute).

Preview locally:
- Install Ruby and bundler, then bundle install (if you want a local Jekyll build).
- Or simply push and let GitHub Pages build.

Notes:
- We're using the remote theme `mmistakes/minimal-mistakes`. If you want a fancier one-page layout (header nav with smooth scroll, section-specific styling, or special home config from Minimal Mistakes) I can add the corresponding layout and data files and sample nav.
