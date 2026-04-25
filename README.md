# 🏝 Bali Cut — 10-Day Protocol App

A mobile-first PWA (Progressive Web App) for the 10-day Bali cut nutrition protocol. Designed to be saved to your iPhone home screen and used like a native app.

## Features

- 📅 10-day meal plan with per-day navigation
- 🥗 Every meal with exact amounts (oz/cups), prep notes, and macros
- 💊 Peptide stack timing (Retatrutide, MOTS-c) built into each day
- 🔁 Refeed day (Day 3) with strategic carb loading
- 📴 Works fully offline once installed
- 📱 iPhone PWA — add to home screen for full-screen experience

## How to Install on iPhone

1. Deploy to GitHub Pages (see below) or open the `index.html` file in Safari
2. In Safari, tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the app icon appears on your home screen
5. Open it — it runs full screen like a native app

## Deploy to GitHub Pages (recommended)

```bash
# 1. Create a new repo on GitHub (e.g. "bali-cut")
# 2. Clone it and copy these files in
git clone https://github.com/YOUR_USERNAME/bali-cut.git
cd bali-cut

# 3. Copy all files from this folder into the repo
# 4. Push to main
git add .
git commit -m "Initial commit"
git push origin main

# 5. Go to repo Settings → Pages → Source: Deploy from main branch → / (root)
# 6. Your app will be live at: https://YOUR_USERNAME.github.io/bali-cut/
```

Once it's live, open that URL in Safari on your iPhone and add to home screen.

## File Structure

```
bali-cut/
├── index.html        # Main app (all HTML, CSS, JS in one file)
├── manifest.json     # PWA manifest (app name, icons, display mode)
├── sw.js             # Service worker (offline caching)
├── logo.svg          # App logo (barbell with BALI CUT text)
├── icons/
│   ├── icon-192.png  # Home screen icon (small)
│   └── icon-512.png  # Home screen icon (large / splash)
└── README.md
```

## Nutrition Protocol Summary

| Day | Type | Protein | Carbs | Cals |
|-----|------|---------|-------|------|
| 1 Mon | Training (Back/Bi) | 218g | 98g | ~1,566 |
| 2 Tue | Rest | 205g | 42g | ~1,344 |
| 3 Wed | **Refeed** + KB | 203g | 182g | ~1,915 |
| 4 Thu | Rest | 199g | 35g | ~1,237 |
| 5 Fri | Training (Legs) | 211g | 105g | ~1,625 |
| 6 Sat | Training (Chest+Cali) | 230g | 90g | ~1,646 |
| 7 Sun | Training (Chest+Tri) | 202g | 95g | ~1,459 |
| 8 Mon | Training (Back/Bi) | 211g | 101g | ~1,609 |
| 9 Tue | Rest | 205g | 33g | ~1,234 |
| 10 Wed | Training (KB) · Final | 221g | 111g | ~1,598 |

## Stack

- **Retatrutide 1.2mg** — Sunday + Wednesday
- **MOTS-c** — Monday, Wednesday, Friday at 3:30 PM (ends Apr 25)
- **CJC/Ipa** — STOPPED (Apr 21)

---

Built with ❤️ and gold.
