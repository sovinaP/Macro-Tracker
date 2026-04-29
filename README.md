# NourishOS

A privacy-first nutrition tracker that runs entirely in your browser.

No account. No subscription. No backend. Just open it and start logging.

## v1.0 Public Beta

NourishOS is now in **public beta**. This release brings the main repo up to date with the current app experience, including smarter food search, better serving controls, micronutrient visibility, reusable meal templates, water tracking, and a more complete goal-setting flow.

## What NourishOS does

NourishOS helps you:

- Log foods by meal.
- Track calories, protein, carbs, fat, and fiber.
- Search foods from USDA FoodData Central.
- Optionally switch to Open Food Facts for more packaged foods.
- Choose serving sizes and units before adding food to your log.
- View daily progress against calorie and macro targets.
- Use the Goal Wizard to estimate targets for cutting, maintaining, or lean bulking.
- Save custom foods for fast re-logging.
- Save full days as meal templates and reuse them later.
- Track daily water intake.
- Log bodyweight by day.
- Review recent history with charts and summary tables.
- Export and import your data as a JSON backup.

## Why it is different

Most nutrition apps push accounts, subscriptions, cloud sync, and locked features.

NourishOS takes a simpler approach:

- Your data stays in your browser.
- There is no required sign-in.
- There is no hosted backend storing your logs.
- The app is lightweight and fast.
- It can be deployed as a single static site.

## Key features

### Food logging
- Search foods by name.
- Pull nutrition data from USDA FoodData Central.
- Switch between USDA and Open Food Facts from the search bar.
- Auto-fill macros from selected food results.
- Adjust quantity and serving unit before logging.
- Fall back to manual entry whenever needed.

### Daily tracking
- Calories, protein, carbs, fat, and fiber.
- Live progress bars against your targets.
- Food log organized by meal.
- Quick view of recent daily history.
- Seven day calorie trend chart.

### Smarter nutrition detail
- Expand macro cards to inspect more detailed nutrient information.
- View micronutrient breakdowns when source data is available.
- Refresh entries with fuller USDA nutrient data when needed.
- See when values come from lower-trust non-USDA sources.

### Planning tools
- Goal Wizard for cut, maintain, and lean bulk targets.
- Support for bodyweight, activity level, body fat, and protein preference inputs.
- Manual target overrides for full control.
- Goal weight and rate-of-change support.

### Reuse and convenience
- Save custom foods for one-tap reuse.
- Save entire days as meal templates.
- Reapply templates to future dates.
- Export or import your full app data as a backup file.

### Lifestyle tracking
- Daily water tracker with quick-add buttons and custom amounts.
- Adjustable water goal and unit selection.
- Daily weight logging with lb or kg support.

### UI and deployment
- Light and dark mode.
- Additional theme presets.
- Mobile-friendly single page layout.
- Works well as a GitHub Pages project.
- Can be added to an iPhone home screen for an app-like experience.

## Privacy

NourishOS is designed to keep your nutrition data under your control.

- Data is stored locally in your browser using local storage.
- No account is required.
- No personal nutrition log is sent to your own server.
- Food searches call public food data sources only when you search.

## Tech stack

- HTML
- CSS
- Vanilla JavaScript
- Browser localStorage
- Chart.js
- Lucide Icons
- GitHub Pages

## Getting started

### Run locally

Clone the repo and open the main HTML file in your browser.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
open index.html
