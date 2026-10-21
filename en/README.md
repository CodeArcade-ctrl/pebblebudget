# PebbleBudget

**A calm, local expense planner.** PebbleBudget helps people keep a simple monthly budget and expense overview without connecting a bank account.

## Problem and audience

Small purchases are easy to forget, and not everyone wants to connect a bank account to an app. PebbleBudget is for anyone who prefers to maintain a simple monthly overview by hand.

## Run

Open `index.html` in a modern browser. No installation, account, server, API, or build step is needed. The Dutch version is in the repository root.

## Features

- Set a monthly budget and see spending, remaining balance, and budget progress.
- Add expenses with a description, amount, date, and category.
- Filter expenses by month and delete entries.
- Export a JSON backup.

## Quick demo

1. Open `index.html` and set a monthly budget.
2. Add a fictional expense, such as `Lunch` for `12.50`.
3. Check the monthly total and remaining budget, then use **Export data** to download a backup.

To start over, clear this page's local site data in your browser. This permanently removes the saved data.

## Privacy and limitations

All information is stored in this browser's `localStorage` and is not sent anywhere. Data is not encrypted and may be lost if browser data is cleared. Avoid storing bank account numbers or other sensitive details. PebbleBudget does not connect to a bank and does not provide financial advice.

## Technology

Vanilla HTML, CSS, and JavaScript; no external dependencies.

## Possible next steps

- Restore a backup from a JSON file.
- Add custom categories.
- Create a printable monthly summary.
