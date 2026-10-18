# Sushi Baghdad website

Static site. Upload the contents of this folder to the repository root and enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

Keep the empty `.nojekyll` file: without it GitHub Pages skips the `_ds/` folder and the site loads unstyled.

`index.html` redirects to `Home v2.dc.html`. Keep all files and folders together; the pages load `support.js`, `_ds/` and `assets/` by relative path.
