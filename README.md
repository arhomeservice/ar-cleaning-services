# AR Cleaning Services — Management Platform

Static single-file app. No build step. Your full history (2,585 bookings) is pre-loaded.

## Run locally
Open `index.html` in any modern browser (Chrome/Edge/Safari). Data saves in the browser (localStorage).

## Deploy to Vercel
Option A (fastest): https://vercel.com/new → drag this folder onto the page → Deploy.
Option B: push this folder to a GitHub repo, then import the repo in Vercel (framework: Other, no build command).

## Data & backups
- Everything is stored in the browser where you use the app.
- Use the header **Backup** button (or Settings → Data Tools) regularly to download a JSON snapshot.
- Settings → Data Tools → Import Excel Workbook, for future exports.
- One live database shared across devices requires the Supabase step (ask me when ready).

## Roles reminder
Admin = owner. Manager = office ops. Staff = booking entry. Driver = pickup schedule. Cleaner = own schedule.
