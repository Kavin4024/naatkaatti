# நாட்காட்டி — Install as a Real App

This folder is a complete PWA (Progressive Web App). To turn it into an
installable app on your phone (with offline support and a real install
prompt), it needs to be hosted on a real web address — phones won't offer
"Install" for a file opened straight from your Downloads folder.

## Easiest free hosting: GitHub Pages (~5 minutes, no coding)

1. Go to github.com and create a free account if you don't have one.
2. Create a new repository (e.g. `naatkaatti`), set it to **Public**.
3. Upload all the files in this folder (`index.html`, `manifest.json`,
   `sw.js`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`) —
   use "Add file → Upload files" on the repo page.
4. Go to the repo's **Settings → Pages**, set Source to the `main` branch,
   root folder, and save.
5. GitHub gives you a link like:
   `https://yourusername.github.io/naatkaatti/`
6. Open that link on your phone in Chrome (Android) or Safari (iPhone).

## Installing on your phone

**Android (Chrome):** open the link → you should see an **"Install app"**
banner automatically, or tap ⋮ → **Install app**.

**iPhone (Safari):** open the link → tap Share → **Add to Home Screen**.

Once installed, it opens full-screen with your kolam icon, works offline
(your data is saved locally either way), and behaves like a native app.

## Want an actual .apk file instead?

If you'd rather have a real installable Android APK (to sideload without
using GitHub Pages), use **pwabuilder.com** — paste your hosted GitHub
Pages link there and it will generate a signed APK / Play Store package for
you automatically, for free.
