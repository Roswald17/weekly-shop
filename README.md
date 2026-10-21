# Weekly Shop — offline app

Files: index.html (the app), sw.js (offline cache), manifest.json + icons (home-screen app).

Host free on GitHub Pages:
1. New public repo, e.g. `weekly-shop`. Upload all files to the root.
2. Settings → Pages → Source: "Deploy from a branch" → main / (root) → Save.
3. After ~1 min it's live at https://<username>.github.io/weekly-shop/

On iPhone (Safari only):
1. Open that link in Safari, wait for it to load fully once.
2. Share → Add to Home Screen → Add.
3. Open it from the home screen once while online. After that it works offline.

Updating: edit index.html, change VERSION in sw.js (e.g. v2), push. Open the app online once to pick it up.
Your prices/ticks live on the phone and survive updates.
