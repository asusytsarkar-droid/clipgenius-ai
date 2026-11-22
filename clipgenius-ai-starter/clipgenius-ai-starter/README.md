# ClipGenius AI — starter website

This is the first **visual website prototype** for ClipGenius AI. It is responsive for mobile, tablet and desktop.

## Important: what works now
- Responsive landing page
- Navigation links to page sections
- Proposed Free / Pro / Business pricing display
- Static editor-style preview

## Not connected yet
This starter is **not yet a working video editor or AI service**. Login, uploads, real caption generation, video rendering, subscriptions, payment processing and AdSense are not implemented. Pricing and usage limits are proposals and should not be advertised as live features until the backend is built and tested.

## Preview locally
Open `index.html` in a browser.

## Publish with GitHub + Cloudflare Pages
1. Sign in to GitHub and create a new repository named `clipgenius-ai`.
2. Upload `index.html`, `styles.css`, `script.js`, and `README.md` to the repository root.
3. Create/sign in to a Cloudflare account.
4. In Cloudflare Dashboard, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
5. Choose the `clipgenius-ai` repository.
6. Framework preset: **None**. Build command: leave blank. Build output directory: `/` (or the repository root, depending on the dashboard prompt).
7. Deploy. Cloudflare will provide a `*.pages.dev` preview address.

Keep API keys and secrets out of GitHub. When we add authentication, AI, storage and payments, use server-side functions and environment secrets.

## Next development steps
1. Add authentication and database.
2. Add secure video upload and file-size/duration limits.
3. Add caption transcription and a browser-based caption editor.
4. Add rendering/export pipeline.
5. Add AI clipping for paid plans, with cost controls.
6. Add subscription payments and server-verified plan limits.
7. Add policy pages, original helpful content and AdSense only after the site is genuinely useful and ready for review.
