# NourishOS

> A lightweight, privacy-first macro and nutrition tracker that runs entirely in your browser — no account, no server, no subscription.

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
2. Tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **Add to Home Screen**
4. Name it **NourishOS** and tap **Add**

It will behave like a native app — full screen, no browser chrome, and launches instantly from your home screen.

---

## What It Does

NourishOS lets you log meals, track macros, set personal nutrition targets, and monitor your weight — all from a single HTML file. Your data lives in your browser's local storage and never leaves your device.

---

## Features

- **🍽️ Combined food search** — search USDA FoodData Central and Open Food Facts together from one search bar.
- **📊 Macro tracking** — calories, protein, carbs, fat, and fiber with live progress bars.
- **⭐ Custom saved foods** — save any food as a personal chip for one-tap relogging; delete individually or clear all at once.
- **🧠 Goal Wizard** — calculate your TDEE using Mifflin-St Jeor or Katch-McArdle, then dial in targets for a cut, maintain, or bulk.
- **✍️ Manual targets** — override calorie and macro goals anytime without going through the wizard.
- **⚖️ Weight log** — log daily bodyweight and view it alongside intake history.
- **🗓️ 7-day history table** — review the past week of calories, protein, carbs, fat, fiber, and weight at a glance.
- **📈 Calorie trend chart** — visual bar chart of your last 7 days against your calorie target.
- **🎨 Theme support** — dark mode plus selectable theme families.
- **💾 Export / import** — back up and restore your full data as a JSON file at any time.
- **⚡ No install required** — one HTML file, works offline after first load.

---

## Tech Stack

| Layer | Details |
|---|---|
| Frontend | HTML5, CSS custom properties, Vanilla JS (ES2022) |
| Data | Browser localStorage, no backend |
| Food search | [USDA FoodData Central API](https://fdc.nal.usda.gov/) + Open Food Facts |
| Charts | Chart.js (CDN) |
| Icons | Lucide Icons (CDN) |
| Hosting | GitHub Pages |

---

## Your Data Stays Yours

NourishOS does not collect, transmit, or store any personal data on a server — ever.

Everything you log is saved locally in your browser via `localStorage`. The only outbound request is a food name query sent to the USDA FoodData Central API or Open Food Facts when you search — no personal information is included. You can export a full backup of your data at any time from the Tweaks menu at the bottom of the app.

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

1. Fork this repo
2. Go to **Settings > Pages** in your fork
3. Set source to `main` branch, `/ (root)`
4. Your instance will be live at `https://your-username.github.io/Macro-Tracker`

---

## Roadmap

- [x] 💧 Water intake tracking
- [x] 🍱 Meal templates
- [x] 📱 PWA / installable on home screen
- [x] 🍽️ Combined USDA + Open Food Facts search
- [x] 🧪 Micronutrient feature disabled until it is made reliable
- [ ] 📷 Barcode scanning via device camera
- [ ] 🍎 HealthKit / Apple Health export
- [ ] 🟢 Google Fit integration

---

## Release

### v0.7 alpha *(current public alpha release)*
- **Combined search** — USDA and Open Food Facts are searched together from one bar.
- **Micronutrient drawers** — currently disabled while the feature is being cleaned up.
- **Macro tracking** — live bars show calories, protein, carbs, fat, and fiber.
- **Custom foods** — save and reuse foods quickly from the add-food flow.
- **Manual targets** — calorie and macro goals can be edited directly.
- **Stability fixes** — cleaned up broken UI states and button wiring.

### v0.3 alpha
- **Meal templates** — save any logged day as a named template and apply it to any future date with one tap
- **Water tracker** — quick-add buttons (8 oz, 16 oz, 500 ml, custom), daily progress bar, configurable goal and unit

### v0.2 alpha
- **Expanded serving units** — weight, volume, and count options across all foods
- **Custom saved foods** — save, reload, and delete personal foods
- **Goal Wizard improvements** — rate slider, goal weight ETA, protein preference selector
- App renamed to **NourishOS**

### v0.1 alpha
- Initial release — food log, USDA search, macro tracking, weight log, 7-day history, calorie chart, dark/light mode, export/import

---

## License

MIT — use it, fork it, build on it.


---

## Public Alpha Release

Create a GitHub release from the repository page using the newest `v0.7 alpha` tag, mark it as a **pre-release**, and attach the current `index.html` / preview bundle if you want a downloadable asset. GitHub supports published releases with downloadable assets and draft-to-publish release flows. [web:455][web:458][web:460]
