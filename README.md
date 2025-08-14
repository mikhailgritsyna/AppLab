# GitHub Pages starter for TikTok verification

Files included:
- `index.html` — links to Terms/Privacy/Callback
- `terms.html` — basic Terms of Service
- `privacy.html` — basic Privacy Policy
- `callback.html` — shows the `code` from TikTok OAuth

## How to use
1) Create a public repo called `<your-username>.github.io` on GitHub.
2) Upload these files to the root of the repo and commit.
3) Go to repo Settings → Pages → ensure it is published on `https://<your-username>.github.io/`.
4) Use the following URLs in TikTok Developer Portal:
   - Terms: `https://<username>.github.io/terms.html`
   - Privacy: `https://<username>.github.io/privacy.html`
   - Redirect URL: `https://<username>.github.io/callback.html`
5) For URL ownership verification (URL prefix), download the signature HTML file from TikTok verification dialog and upload it to the repo root **without changing its name**. Then click Verify in TikTok.
