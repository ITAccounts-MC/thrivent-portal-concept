# Thrivent Life-Stage Portal — Concept (Modern Climate)

Static site. No build step. Netlify publishes the repo root.

- `index.html` — the scrolling presentation
- `brand/style-guide.html` — brand & style guide
- `brand/screens.html` — look-and-feel sample screens

Concept only: illustrative, not a live Thrivent product. Pages are set to `noindex`.
Keep the repo private and the Netlify site password-protected.

## Settings (config.js)

`config.js` sits next to `index.html`. Open it in any text editor:

- `confidentialityScreen: true` shows the "Before we go further" screen before Kari's story.
- `confidentialityScreen: false` skips it; the presentation flows straight into the story.

Save, commit and push; Netlify redeploys. The file is served with `no-cache`, so changes show on the next page load.
Adding `?present` to the URL also skips the screen for that visit, regardless of the setting.
