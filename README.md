# NourishOS

> Your personal nutrition OS.  
> A privacy-first macro tracker that runs entirely in the browser with no account, no backend, and no subscription.

<p align="center">
  <a href="https://github.com/YOUR-USERNAME/YOUR-REPO/releases">
    <img src="https://img.shields.io/badge/release-v1.0%20Public%20Beta-0f766e?style=for-the-badge" alt="Release">
  </a>
  <a href="https://choosealicense.com/licenses/mit/">
    <img src="https://img.shields.io/badge/license-MIT-166534?style=for-the-badge" alt="License">
  </a>
  <a href="https://pages.github.com/">
    <img src="https://img.shields.io/badge/deploy-GitHub%20Pages-334155?style=for-the-badge" alt="Deploy">
  </a>
  <a href="https://developer.mozilla.org/">
    <img src="https://img.shields.io/badge/built%20with-HTML%20%2B%20CSS%20%2B%20Vanilla%20JS-f59e0b?style=for-the-badge" alt="Built With">
  </a>
</p>

<p align="center">
  <a href="[https://sovinap.github.io/Macro-Tracker/]"><strong>Web App</strong></a>
  ·
  <a href="#features">Features</a>
</p>

---

## Overview

NourishOS is a lightweight nutrition tracker built for people who want fast logging, clear daily targets, and full control over their own data. It runs as a static web app, stores your logs locally in the browser, and keeps the experience simple instead of turning food tracking into another subscription product.

This release marks the move from the older `v0.7` line to **v1.0 Public Beta**, bringing the main repo up to date with the newer app experience and feature set.

---

## Why NourishOS

Most nutrition apps are bloated, locked behind accounts, or designed to trap your data in someone else’s service.

NourishOS takes the opposite approach:

- No sign-up required.
- No backend required.
- No monthly fee.
- No cloud dependency for your core data.
- No complicated install process.
- Just open the app and start logging.

---

## Features

### Food logging
- Search foods by name from **USDA FoodData Central**.
- Switch to **Open Food Facts** for branded and packaged foods.
- Select serving size and unit before adding food.
- Auto-fill calories, protein, carbs, fat, and fiber from search results.
- Use manual entry anytime when search data is not what you want.

### Daily tracking
- Track calories, protein, carbs, fat, and fiber.
- See live progress bars against your daily targets.
- Organize entries by meal.
- Review recent days in a history table.
- Spot trends with a 7-day calorie chart.

### Better nutrition detail
- Expand macro cards to inspect more detailed nutrient information.
- View micronutrient breakdowns when source data supports it.
- Refresh entries with fuller USDA nutrient data.
- Clearly distinguish lower-confidence non-USDA entries.

### Goal setting
- Use the Goal Wizard for **cut**, **maintain**, or **lean bulk** targets.
- Estimate calories from body stats and activity level.
- Support body fat input for more accurate calculations.
- Choose protein strategy based on bodyweight, lean mass, or custom grams per pound.
- Override targets manually at any time.

### Reuse and convenience
- Save custom foods for one-tap relogging.
- Save full days as meal templates.
- Reuse templates on future dates.
- Export and import your full data as JSON.

### Lifestyle tools
- Track daily water intake with quick-add buttons.
- Set your own water goal and unit.
- Log bodyweight by day in pounds or kilograms.

### Interface
- Light mode and dark mode.
- Extra theme presets.
- Mobile-friendly layout.
- Works well from GitHub Pages.
- Easy to add to an iPhone home screen for app-like use.

---

## Built for privacy

NourishOS is designed so your nutrition data stays under your control.

- Data is stored in browser `localStorage`.
- No account is required.
- No personal logs are stored on your own server.
- The app only makes outbound calls when you search food databases.
- You can export a full backup whenever you want.

That makes it simple, portable, and hard to lose control of.

---

## Tech stack

| Layer | Details |
|---|---|
| Frontend | HTML5, CSS, Vanilla JavaScript |
| Storage | Browser `localStorage` |
| Food sources | USDA FoodData Central, Open Food Facts |
| Charts | Chart.js |
| Icons | Lucide |
| Hosting | GitHub Pages |

---

## Getting started

### Run locally

No build step. No framework. No package install.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
open index.html
