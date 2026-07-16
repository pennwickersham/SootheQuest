[README.md](https://github.com/user-attachments/files/30085431/README.md)
# Soothe Quest — Legal Pages

Privacy Policy and Terms of Use for the Soothe Quest mobile app, hosted via
GitHub Pages while brewsterwickershampublications.com pages are set up.

## ⚠️ Before the links go live — 2 placeholders remain

Both documents still contain:
- `[CONTACT EMAIL]` — the support/privacy contact address
- `[STATE]` — governing-law state in terms-of-use.html §10

Edit those (GitHub web editor is fine), then the pages are ready for store
review.

## Publish with GitHub Pages (≈2 minutes)

1. Create a new **public** repository, e.g. `soothequest-legal`
   (github.com → New repository).
2. Push this folder (see below) or simply drag-and-drop the four files
   (`index.html`, `privacy-policy.html`, `terms-of-use.html`, `README.md`)
   onto the repo page → Commit.
3. Repo **Settings → Pages** → Source: `Deploy from a branch` →
   Branch: `main`, folder `/ (root)` → Save.
4. After ~1 minute your URLs are live:

```
https://<your-username>.github.io/soothequest-legal/privacy-policy.html
https://<your-username>.github.io/soothequest-legal/terms-of-use.html
```

Paste those into App Store Connect (App Privacy → Privacy Policy URL, and
the EULA/Terms field) and Google Play Console (Store listing → Privacy
policy). Store URLs are editable later, so when the pages move to
brewsterwickershampublications.com/soothequest/, just update the consoles.

## Pushing from the command line (alternative to drag-and-drop)

```bash
git remote add origin https://github.com/<your-username>/soothequest-legal.git
git push -u origin main
```

(This folder is already a git repository with the initial commit made.)
