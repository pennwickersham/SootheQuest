# Soothe Quest website

Static site: marketing landing page + privacy policy + terms of use.
No build step — upload as-is.

## Deploy (easiest: your existing GitHub Pages repo)

Upload ALL of these files/folders into the same repository that hosts the
legal pages (drag-and-drop on github.com works — include the `assets`
folder). The new `index.html` replaces the old plain landing page, and
`privacy-policy.html` / `terms-of-use.html` keep the same filenames — so
any URLs already pasted into the store consoles keep working unchanged.

Live at: https://YOUR-USERNAME.github.io/YOUR-REPO/

## Two things to update

0. **Product links** are live: theresilientpathbook.com, rheumcompanion.com.
1. **Store buttons** (index.html): at launch, replace the two `href="#"`
   store buttons with the real App Store / Google Play URLs and delete the
   "Launching soon" lines.
2. **terms-of-use.html §10**: replace [STATE] with your governing-law state.

## Notes

- Fonts (Fredoka + Nunito — the game's own typefaces) load from Google
  Fonts when the site is online.
- The hero lantern's glow "breathes" on the game's 4-second box-breathing
  cadence; it respects visitors' reduced-motion settings.
- Screenshots in `assets/` are real captures from the game.
