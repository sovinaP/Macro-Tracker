# NourishOS

> A lightweight, privacy-first macro and nutrition tracker that runs entirely in your browser. No account, no server, no subscription.

[![Version](https://img.shields.io/badge/version-v0.7%20alpha-blue)](https://github.com/sovinap/Macro-Tracker)
[![License](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit/)
[![Built With](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20Vanilla%20JS-orange)](https://developer.mozilla.org)
[![Deployment](https://img.shields.io/badge/deployed%20on-GitHub%20Pages-lightgrey)](https://pages.github.com)

---

## Use It Now

**[sovinap.github.io/Macro-Tracker](https://sovinap.github.io/Macro-Tracker/)**

No sign up. No install. Just open and start logging.

### Add to your iPhone home screen (Safari)
1. Open the link above in **Safari**
2. Tap the **Share** button
3. Scroll down and tap **Add to Home Screen**
4. Name it **NourishOS** and tap **Add**

It will behave like a native app, full screen, no browser chrome, and launches instantly from your home screen.

---

## What It Does

NourishOS lets you log meals, track macros, set nutrition targets, monitor water, track weight, and save meal templates, all from a single HTML file. Your data lives in your browser's local storage and never leaves your device.

---

## Features

- **Daily food log** - search foods via the USDA FoodData Central API with serving size and unit selection.
- **Dual food database** - toggle between USDA and Open Food Facts directly in the search bar; both sources normalize into the same macro flow.
- **Macro tracking** - calories, protein, carbs, fat, and fiber with live progress bars.
- **Micronutrient drawers** - tap any macro card to expand a detailed micronutrient breakdown with live DRI progress bars.
- **Micronutrient refresh** - rescan the current day and backfill entries with full USDA nutrient data in batches using the Refresh button in the footer.
- **Custom saved foods** - save any food as a personal chip for one-tap relogging; delete individually or clear all at once.
- **Goal Wizard** - calculate your TDEE using Mifflin-St Jeor or Katch-McArdle, then dial in targets for a cut, maintain, or bulk.
- **Manual targets** - override calorie and macro goals anytime without going through the wizard.
- **Weight log** - log daily bodyweight and view it alongside intake history.
- **Water tracker** - quick-add buttons, custom amounts, and a daily goal bar.
- **Meal templates** - save a day as a reusable template.
- **7-day history table** - review the past week of calories, protein, carbs, fat, fiber, and weight at a glance.
- **Calorie trend chart** - visual bar chart of your last 7 days against your calorie target.
- **Theme families** - use Light or Dark mode from Appearance, then choose a theme family like Forest, Sunset, or Slate.
- **Export / import** - back up and restore your full data as a JSON file at any time.
- **No install required** - one HTML file, works offline after first load.

---

## Theme System

Use the **Appearance** button to switch between Light mode and Dark mode.

Use the **Themes** row to pick a theme family such as Forest, Sunset, or Slate.

Each theme family now has both Light and Dark variants, so the UI stays consistent in either mode.

---

## Tech Stack

| Layer | Details |
|---|---|
| Frontend | HTML5, CSS custom properties, Vanilla JS (ES2022) |
| Data | Browser localStorage, no backend |
| Food search | USDA FoodData Central API + Open Food Facts |
| Charts | Chart.js (CDN) |
| Icons | Lucide Icons (CDN) |
| Hosting | GitHub Pages |

---

## Your Data Stays Yours

NourishOS does not collect, transmit, or store personal data on a server.

Everything you log is saved locally in your browser via `localStorage`. The only outbound request is a food name query sent to the USDA FoodData Central API or Open Food Facts when you search. No personal information is included.

You can export a full backup of your data at any time from the Tweaks menu at the bottom of the app.

---

## Getting Started

### Run it locally

No build step. No dependencies. Just clone and open:

```bash
git clone https://github.com/sovinap/Macro-Tracker.git
cd Macro-Tracker
open index.html
```

### Fork and deploy your own instance

1. Fork this repo.
2. Go to **Settings > Pages** in your fork.
3. Set source to `main` branch, `/ (root)`.
4. Your instance will be live at `https://your-username.github.io/Macro-Tracker`.

---

## Roadmap

- [x] Water intake tracking
- [x] Meal templates
- [x] PWA / installable on home screen
- [x] Dual food database (USDA + Open Food Facts)
- [x] Micronutrient breakdown per macro card
- [x] Theme families with Light and Dark variants
- [ ] Barcode scanning via device camera
- [ ] HealthKit / Apple Health export
- [ ] Google Fit integration

---

## Release

### v0.7 alpha *(current public alpha release)*
- Theme presets now work as actual UI themes instead of just button labels.
- Light and Dark were separated from the Themes list and moved to Appearance.
- Theme families now adapt to both Light and Dark mode.
- Active theme styling was cleaned up so it stays readable in either mode.
- A null-safe fix was added for the micro modal event binding.

### v0.6 alpha
- Macro detail panels let you tap any macro card to view goal progress and top contributing foods.
- Optional nutrient details show a secondary nutrients view when trustworthy data exists.
- Mixed-source awareness flags entries from community or non-USDA sources.
- Batched rescan processes entries in parallel batches instead of one at a time.
- Dual food database support lets you toggle between USDA and Open Food Facts.
- Critical bug fix resolved a silent JavaScript error on page load.

### v0.3 alpha
- Meal templates let you save any logged day as a named template and apply it to future dates.
- Water tracker added quick-add buttons, a daily progress bar, and configurable goal and unit.

### v0.2 alpha
- Expanded serving units across foods.
- Custom saved foods with save, reload, and delete support.
- Goal Wizard improvements with rate slider, goal weight ETA, and protein preference selector.
- App renamed to NourishOS.

### v0.1 alpha
- Initial release with food log, USDA search, macro tracking, weight log, 7-day history, calorie chart, dark/light mode, and export/import.

---

## License

MIT. Use it, fork it, build on it.
