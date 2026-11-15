# Daily Expense Tracker (PWA)

An offline-first personal finance and daily expense tracker built as a single-file Progressive Web App (PWA) for INR (₹). Designed to run smoothly on mobile and desktop with local browser storage and optional cloud sync.

## Features

- **Accounts & Balances:** Track bank accounts, cash in hand, credit cards (with available limits and due dates), transfers, withdrawals, and loans.
- **Fast Expense Logging:** One-line Quick Type input (`milk 60 cash`), Quick-Add shortcuts, duplicate detection, and **split purchases** across multiple categories.
- **Custom Categories & Bulk Actions:** Add, rename, hide, or merge categories and sub-categories, plus multi-select in Activity for bulk category changes, tagging, or deletion.
- **Budgets & Forecasting:** Category and monthly-repeat tag budgets, budget suggestions from recent history, month-end cash-flow projection, and a **Year in Review** summary.
- **Recurring Bills & Calendar Export:** Manage recurring income/expenses and export due dates as `.ics` calendar files.
- **Backup & Privacy:** JSON export/import, 7-day backup reminders, Recently Deleted restore bin, Dark/Light themes, and a 4-digit PIN / WebAuthn biometric App Lock.

## Project Structure

- `index.html` — Complete self-contained application (HTML, CSS, and JavaScript).
- `manifest.json` — PWA metadata and icon configuration.
- `service-worker.js` — Offline caching for standalone installation.
- `icons/` & `favicon.ico` — App icons for Android, iOS, and desktop.

## Hosting & Installation

1. Host the repository on any HTTPS static host (such as **Netlify** or **GitHub Pages**).
2. Open the live URL in Chrome or Safari on your phone and tap **Add to Home Screen / Install App** to use it like a native app offline.
