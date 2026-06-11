# Cut Tracker

Simple intake tracker for logging:

- what you ate or drank
- calories
- time added

## Run locally

From this folder:

```bash
npm run serve
```

Then open:

```text
http://localhost:4173
```

## Put it on your phone

For a real installable app experience, host this folder on an HTTPS site such as GitHub Pages, Netlify, or Vercel.

Once it is hosted:

- On iPhone: open the site in Safari, tap Share, then `Add to Home Screen`
- On Android: open the site in Chrome and tap `Install App` when prompted

## Files

- `index.html`: app UI and tracking logic
- `manifest.webmanifest`: install metadata
- `service-worker.js`: offline support
- `icons/`: app icons
