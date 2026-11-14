# Four Card Draw

A random card drawer. Each draw shuffles a fresh 52-card deck and draws 4 cards, so no card repeats in a draw.

- **Shuffle & draw 4** (or press Space) makes a new draw from a new full deck.
- The hand is rated by rarity over all 270,725 possible 4-card hands:
  high card, one pair, flush, two pair, straight, three of a kind, straight flush, four of a kind (most common to rarest).
- **Draw order** is a bonus: cards drawn sorted by rank (low to high or high to low) make the result rarer.
- Each draw shows its exact odds, a tier (Common to Legendary), a rarity score (0–100) and the percent of poker hands it beats.
- The last 10 draws are kept in the browser.

Card art: [Playing Cards Pack](https://kenney.nl/assets/playing-cards-pack) by Kenney, CC0 (see `cards/LICENSE-Kenney.txt`).

The older Pixel Roller (random 32×32 pixel paintings) is at `pixel-roller.html`.

All files are static, no build step.

## Use on a phone

Live site: https://witherik.github.io/random-color/

GitHub Pages deploys it from the `main` branch. Every push to `main` updates the site.
