# Looping meets blue chip — X player card

## Files
- `index.html` — the interactive card (640×480, self-contained, no build step)
- `poster.png` — 1280×960 still shown before the card is opened, and on mobile

## Publish
1. Host this folder on any HTTPS static host (GitHub Pages, Vercel, Netlify, Cloudflare Pages), e.g. `https://example.com/looping/`.
2. In `index.html`, replace every `https://YOUR-DOMAIN/looping/` with that URL, and `@YOUR_HANDLE` with the Corda X handle.
3. The host must allow framing: no `X-Frame-Options` header and no `Content-Security-Policy: frame-ancestors` restriction. GitHub Pages is fine by default. On Vercel/Netlify, check that no security-header preset adds these.
4. Check the page loads directly, then post the URL on X.

## What to expect
- Desktop web: the post shows the poster; clicking it loads the interactive chart inline.
- Mobile apps: usually show the poster and open the page in the browser.
- X officially describes player cards for audio/video and has historically required domain approval. Inline interactive rendering is current behaviour, not a guarantee, and may change.
