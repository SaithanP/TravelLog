# Field Journal — PWA Setup Guide

## Files in this folder
- `index.html` — the full app
- `manifest.json` — PWA metadata (name, icon, theme)
- `sw.js` — service worker (enables offline use)

---

## How to host for free (Netlify Drop — easiest)

1. Go to **https://app.netlify.com/drop** on any browser
2. Drag the entire `field-journal` folder onto the page
3. Netlify gives you a free URL like `https://random-name.netlify.app`
4. Open that URL in **Chrome on your Android tablet**
5. Tap the **⋮ menu → "Add to Home Screen"**
6. Done! The app installs with its own icon and works offline.

---

## Alternative: GitHub Pages

1. Create a free account at github.com
2. New repository → upload all 3 files
3. Settings → Pages → Deploy from main branch
4. Your URL: `https://yourusername.github.io/field-journal`

---

## Notes
- All your data is saved locally on the tablet (localStorage)
- Works fully offline after first load
- No account or login needed
