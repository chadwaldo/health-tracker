# Health Tracker

**The Daily Ledger** — a single-file daily health tracker (weight, meals, exercise, streak, goals).
All data is stored locally in the browser via `localStorage`; nothing is sent anywhere.

## Live page

Hosted on GitHub Pages: https://chadwaldo.github.io/health-tracker/

Add it to your iPhone home screen (Share → *Add to Home Screen*) to open it like an app.

## Data & backups

All entries live in the browser's `localStorage` on the device you use — nothing syncs.
Use **Export data** in the footer to save a JSON backup, and **Import data** to restore it
(or move it to another device). An import replaces current data and stashes the previous
copy under `daily-ledger-data-prev` as a one-step undo.

## Files

- [`index.html`](index.html) — the entire app, no build step, no dependencies.
