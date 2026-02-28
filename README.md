# flo. — Zero-Based Budget App

A beautiful, YNAB-inspired budgeting app built as a Progressive Web App (PWA). Works on iPhone, Android, and desktop. No subscriptions, no tracking — your data stays on your device.

## Features

- **Zero-based budgeting** — assign every dollar of income to a category
- **Spending limits** — set caps per category with 80% and 100% warnings
- **Transaction tracking** — log income and expenses, auto-updates account balances
- **Goals & savings targets** — track progress with monthly contribution calculator
- **Accounts** — chequing, savings, credit, TFSA, RRSP
- **Reports** — spending by category, 6-month income vs expenses, savings rate
- **Offline support** — works with no internet connection (PWA)
- **Export / Import** — sync between devices via JSON file

## Install on iPhone

1. Open your GitHub Pages URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add** — done!

## Sync Between Devices

1. On laptop: tap **↑ Export** → saves `flo-budget-YYYY-MM.json`
2. Upload to iCloud Drive (or AirDrop to iPhone)
3. On iPhone: tap **↓ Import** → pick the file
4. Both devices are now in sync ✓

## Currency

CAD (Canadian Dollar) — all amounts display as `CA$`

## Tech

Plain HTML + CSS + JavaScript. No frameworks, no build step, no dependencies.
Data stored in `localStorage` — private to your browser.
