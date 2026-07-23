# Valentine

Static Valentine's Day card — open/close envelope animation with jQuery.

## Stack

- **jQuery 3.6.1** (CDN) — all interactivity
- **HTML/CSS/JS** — no build step, no package manager

## Files

- `index.html` — structure, loads jQuery from CDN
- `index.css` — envelope styling, flap animation, heart particle effects
- `index.js` — open/close toggle via jQuery class manipulation

## Run

Open `index.html` in a browser. No server needed for local dev.

## Conventions

- Text is in Russian (personal message). Editing content changes the card's recipient.
- Animations rely on CSS classes `open` / `close` on `#envelope`. JS toggles these; CSS handles transitions.
- Hearts animate on open via CSS `@keyframes slideUp`. They only appear in the `open` state.
