# Ocean

Music site: songs, photos and a live remix studio. Plain HTML, no build step.

## Publish on GitHub Pages
1. Create a new repository and upload everything in this folder (keep `photos/` and `media/` next to `index.html`).
2. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", pick `main` and `/ (root)`, and save.
3. The site appears at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Notes
- `.nojekyll` tells GitHub to serve the files as-is.
- To use your own domain, add it under Settings → Pages (GitHub creates a `CNAME` file).
- For link previews on social media, change `og:image` in `index.html` to the full address of `photos/bridge.jpg` once the site is live.
- Songs live in `media/`, photos in `photos/`. Every file is well under GitHub's 100 MB limit.
