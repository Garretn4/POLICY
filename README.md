# Alpine Life Solutions — Website

Static site for Alpine Life Solutions LLC. Three pages:

- `index.html` — home / landing
- `privacy-policy.html` — Privacy Policy (with SMS opt-in carve-out for A2P)
- `terms.html` — Terms of Service (with SMS messaging terms)

No build step, no dependencies. Pure HTML/CSS. Hosts free on GitHub Pages.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `alpine-life-site`). Public.
2. Upload all three `.html` files (and this README) to the repo root.
   - Either drag-and-drop in the GitHub web UI ("Add file" → "Upload files"), or push via git.
3. In the repo: **Settings → Pages**.
4. Under "Build and deployment" → Source: **Deploy from a branch**.
5. Branch: **main**, folder: **/ (root)**. Save.
6. Wait ~1 minute. GitHub gives you a live URL like:
   `https://YOUR-USERNAME.github.io/alpine-life-site/`

Your pages are then live at:
- `https://YOUR-USERNAME.github.io/alpine-life-site/`
- `https://YOUR-USERNAME.github.io/alpine-life-site/privacy-policy.html`
- `https://YOUR-USERNAME.github.io/alpine-life-site/terms.html`

## (Optional) Use your own domain — alpinelifesolutions.com

1. In repo **Settings → Pages → Custom domain**, enter `www.alpinelifesolutions.com`. Save.
2. At your DNS host (wherever alpinelifesolutions.com DNS is managed), add a
   **CNAME** record: `www` → `YOUR-USERNAME.github.io`.
3. Back in Pages, check **Enforce HTTPS** once the cert provisions.

Then your A2P website URL becomes `https://www.alpinelifesolutions.com`.

## For A2P / 10DLC submission

Use the privacy policy URL as your supporting doc. The carve-out language
("No mobile information will be shared with third parties/affiliates for
marketing/promotional purposes...") is present in Section 3 and the top notice,
which is what TCR vetting checks for.
