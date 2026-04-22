# NourishOS

> A lightweight, privacy-first macro and nutrition tracker that runs entirely in your browser — no account, no server, no subscription.

![Version](https://img.shields.io/badge/version-v0.2%20alpha-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20Vanilla%20JS-orange)
![Deployment](https://img.shields.io/badge/deployed%20on-GitHub%20Pages-lightgrey)

---

## What It Does

NourishOS lets you log meals, track macros, set nutrition targets, and monitor your weight — all from a single HTML file. Your data lives in your browser's local storage and never leaves your device.

---

## Features

- **Daily food log** — search 300,000+ foods via the USDA FoodData Central API, with serving size and unit selection
- **Macro tracking** — calories, protein, carbs, fat, and fiber with live progress bars
- **Custom saved foods** — save any food as a personal chip for one-tap relogging; delete individually or clear all
- **Goal Wizard** — calculate your TDEE using Mifflin-St Jeor or Katch-McArdle, then set targets for cut, maintain, or bulk
- **Manual targets** — override with your own calorie and macro goals anytime
- **Weight log** — log daily bodyweight and view it alongside your intake history
- **7-day history table** — review the past week of calories, protein, carbs, fat, fiber, and weight at a glance
- **Calorie trend chart** — visual bar chart of your last 7 days vs. your calorie target
- **Dark / light mode** — toggles and persists across sessions
- **Export / import** — back up and restore your full data as a JSON file
- **No install required** — one HTML file, works offline after first load

---

## Tech Stack

| Layer | Details |
|---|---|
| Frontend | HTML5, CSS custom properties, Vanilla JS (ES2022) |
| Data | Browser localStorage, no backend |
| Food search | [USDA FoodData Central API](https://fdc.nal.usda.gov/) |
| Charts | Chart.js (CDN) |
| Icons | Lucide Icons (CDN) |
| Hosting | GitHub Pages |

---

## Getting Started

### Use it instantly
Visit the live site: **[your-username.github.io/nourishOS](https://your-username.github.io/nourishOS)**

### Run it locally
No build step needed. Just open the file:

```bash
git clone https://github.com/your-username/nourishOS.git
cd nourishOS
open index.html
```

### Deploy your own fork
1. Fork this repo
2. Go to **Settings > Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://your-username.github.io/nourishOS`

---

## Data & Privacy

All data is stored locally in your browser via `localStorage`. Nothing is sent to any server except outbound food search queries to the USDA FoodData Central API (food name only, no personal data). You can export a full backup at any time from the Tweaks menu.

---

## Roadmap

- [ ] Barcode scanning via device camera
- [ ] Water intake tracking
- [ ] Meal templates
- [ ] PWA / installable offline app
- [ ] HealthKit / Google Fit export

---

## License

MIT — use it, fork it, build on it.
