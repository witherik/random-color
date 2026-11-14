# Pixel Roller

A random 32×32 pixel painting generator with retro palettes.

- **Roll** (or press Space) fills every pixel with a random color from the selected palette.
- Palettes: Sweetie 16, C64, CGA, Green LCD, Amber CRT.
- The last 10 rolls show below the painting. Tap any painting to enlarge it.
- Each roll is stored as a seed, so it is reproducible. History is kept in the browser.

It is one static file (`index.html`), no build step.

## Use on a phone

GitHub Pages: in the repository go to **Settings → Pages → Source: GitHub Actions**.
After a push to `main`, the workflow publishes the site to `https://<owner>.github.io/random-color/`.
