# Velvet Bloom — GitHub Pages Site

This package contains a demo-ready static website for **Velvet Bloom**.

## Included files
- `index.html` — The full site (demo cart; no real payments).
- `images/` — Product images and logo:
  - `body_mist.jpg`
  - `blush.jpg`
  - `lip_gloss.jpg`
  - `logo.png`
- `README.md` — This file.

## How to publish on GitHub Pages
1. Create a new public repository on GitHub, e.g. `velvet-bloom`.
2. Upload the contents of this ZIP to the repository root. You can drag & drop:
   - `index.html`
   - the `images/` folder
   - `README.md`
3. In the repository, go to **Settings → Pages**.
4. Under **Source**, select the `main` branch and the `/ (root)` folder.
5. Save. After ~30-60 seconds, your site will be live at:
   `https://<your-github-username>.github.io/velvet-bloom/`

## Notes
- This is a demo site. Checkout is disabled and shows a demo alert.
- If you want payments, I can provide a Stripe-ready function and instructions to integrate with Netlify or another serverless host.
- The AI Tint Scanner runs in-browser (camera or photo upload) and suggests shades client-side.

If you want me to generate `success.html` and `cancel.html` or convert this into a Netlify-deployable repo with payment integration, tell me and I will prepare it.