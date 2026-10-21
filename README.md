# for kaylyn, in every universe

A complete, standalone romantic website. No dependencies or backend required.

## Open it
Open `index.html` in a modern browser, or serve the directory with `python -m http.server 8000` and visit `http://localhost:8000`.

## Customize
Edit `content.js`:
- `anniversaryStart`: Enter the **actual** anniversary year in ISO 8601 format, e.g. `2026-02-14T00:00:00-05:00`. Until configured, the timer displays a gentle placeholder.
- **Spotify:** The ♫ our song button opens an embedded player for track `3H10bwNwqqfpx6DKvvL6UI`. To change it, replace the track ID in `index.html`. Spotify controls playback and may require a login for full playback.
- `letter` and `reasons`: Edit freely to make the message your own.

## Publish
Upload the contents of this folder to a static host such as Netlify, Cloudflare Pages, or GitHub Pages. No build step is necessary. If using GitHub Pages, publish from the repository root.

## Notes
Spotify playback is user-initiated and requires an internet connection. The site supports reduced-motion settings, keyboard controls, responsive layouts, and touch interactions. The right/left score is session-only and starts at zero. No visitor data is collected.
