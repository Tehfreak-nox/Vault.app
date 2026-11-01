# Vault

A personal budget, spending, and investing tracker. Single-page app, no backend, no account —
everything is stored in your browser's local storage, on your own device.

**Live site:** https://tehfreak-nox.github.io/Vault.app/

## What it does

- **Budget** — monthly income, expenses, and savings goals, with a spending tracker that runs
  against your own pay-period calendar, categorized entries, bills checklist, and a breakdown of
  where the money goes.
- **Investing** — a monthly contribution tracker per stock/ETF, a compound-growth projection tool,
  and a watchlist with live price lookups.
- **Settings** — base currency, pay day, exchange rates, and backup/restore (download your data as
  a file, or copy/paste it as text) so you can move it between devices yourself.

## Install it on your phone

Open the live site above in your phone's browser, then:
- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** menu (⋮) → Add to Home screen / Install app

It'll launch full-screen like a normal app. Your data stays local to whichever device/browser you
used to enter it — use Settings → Backup to carry it over to another device.

## Developing

It's one file: `index.html` (HTML, CSS, and JS inline, no build step, no dependencies). Open it
directly in a browser to work on it. Pushing to `main` publishes the site via GitHub Pages.
