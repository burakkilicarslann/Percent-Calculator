# Percent — Smart Calculator (PWA)

A progressive web app for percentage calculations with 6 modes,
currency support, dark mode, and calculation history.

---

## Files Included

```
pwa-percent/
├── index.html        ← Main app (all-in-one HTML/CSS/JS)
├── manifest.json     ← PWA manifest (app name, icons, theme)
├── sw.js             ← Service worker (offline support)
├── README.md         ← This file
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

---

## How to Deploy (Free) & Install on Your Phone

### Option A: Deploy to Netlify (Easiest — No Account Needed)

1. Go to https://app.netlify.com/drop
2. Drag and drop the entire `pwa-percent` folder
3. Your app is live! You'll get a URL like `https://random-name.netlify.app`
4. Open that URL on your Android phone in Chrome
5. You'll see an "Add to Home Screen" prompt, or tap ⋮ menu → "Install app"
6. Done! The app icon appears on your home screen.

### Option B: Deploy to Vercel

1. Go to https://vercel.com and sign up (free with GitHub)
2. Create a new project → Import from folder
3. Upload the `pwa-percent` folder
4. Vercel gives you a URL → open on your phone → install

### Option C: Deploy to GitHub Pages (Free)

1. Create a GitHub repository (e.g., `percent-calculator`)
2. Upload all files from this folder to the repository
3. Go to Settings → Pages → Source: main branch → Save
4. Your app is at `https://yourusername.github.io/percent-calculator/`
5. Open on phone → Install

---

## How to Get an APK File (Optional)

If you want an actual .apk file instead of browser install:

1. Deploy the app first (using any method above)
2. Go to https://www.pwabuilder.com
3. Paste your app URL
4. Click "Package for stores" → Android
5. Download the APK
6. Transfer to your phone and install
   (Enable "Unknown Sources" in Settings → Security)

---

## Features

- 6 Calculation types (%, add, subtract, discount, VAT, commission)
- 3 Currencies (TL, USD, EUR)
- Quick percentage buttons (1%, 10%, 18%, 20%, 25%, 50%)
- Copy results to clipboard
- Calculation history (saved locally)
- Dark / Light mode
- Works offline after first visit
- Installable as an app on Android and iOS

---

## Customization

- To change colors: edit CSS variables in `:root` and `.dark` in index.html
- To add currencies: add entries to the `CURRENCIES` array in the script
- To add quick buttons: modify the `QUICK` array
- To change app name: edit manifest.json `name` and `short_name`
