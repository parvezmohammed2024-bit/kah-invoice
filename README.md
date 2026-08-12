# Kah Global Invoice System

A single-file invoicing app for Kah Global Sdn Bhd. No server, no database, no installation.

## Features
- A4 invoice output matching the company's standard invoice format (print / save as PDF)
- Customer list with search, add, edit, delete — pick a customer and details auto-fill
- Company settings: name, registration no., address, tel, logo, payment note (bank account)
- Auto-incrementing invoice numbers (INV000073, INV000074, ...)
- Saved invoice history — reopen and reprint any past invoice
- Automatic "Ringgit Malaysia amount in words" line

## How to use
Open `index.html` in any browser (Chrome recommended). That's it.

All data is saved in the browser's local storage on the computer you use it on.

## Hosting on GitHub Pages (optional)
Repo → Settings → Pages → Source: `main` branch, root folder → Save.
The app will be live at `https://<username>.github.io/<repo-name>/`.

## Notes
- Data is stored per browser, per computer. Take PDF copies of invoices as your permanent records.
- Clearing browser data will erase saved customers/invoices — export PDFs regularly.
