# Kah Global Invoice System

A single-file invoicing & quotation app for Kah Global Sdn Bhd. No server, no database, no installation.

## Features
- A4 invoice output matching the company's standard invoice format (print / save as PDF)
- Customer list with search, add, edit, delete — pick a customer and details auto-fill
- Company settings: name, registration no., address, tel, logo, payment note (bank account)
- Auto-incrementing invoice numbers (INV000073, INV000074, ...)
- Saved invoice history — reopen and reprint any past invoice
- Automatic "Ringgit Malaysia amount in words" line
- **Quotations** — separate Quotation tab with its own numbering (QUO000001, ...), "Valid until" date, terms & conditions box, saved quotation history, and one-click **Convert to invoice**, and up to 2 photos per quoted item

## CRM (click **CRM** at the top of the left panel)
Built for a uniform / garment manufacturer:
- **Dashboard** — open pipeline, quotations & sales this month, outstanding money, jobs in production, follow-ups due
- **Sales Pipeline** — drag-and-drop board: New Enquiry → Requirement Brief → Sample / Artwork → Quotation Sent → Negotiation → Won / Lost. Each deal holds product, decoration, fabric, size split, value, lead source. One click creates the quotation.
- **Production** — job board: Order Confirmed → Artwork Approved → Fabric & Trims → Cutting → Sewing → Print / Embroidery → QC → Packing → Delivered. Late jobs flagged, printable factory job sheet, one-click invoice.
- **Customers** — 360° view: deals, quotations, invoices, jobs, follow-ups, size history, one-click reorder, CSV export
- **Follow-ups** — calls, WhatsApp, meetings, sample drops with due dates and WhatsApp links
- **Payments** — record payments against invoices, aging (1–30 / 31–60 / 61–90 / 90+ days), WhatsApp payment reminders
- **Reports** — sales by month, top customers, quote-to-invoice conversion, win rate, lead sources, lost reasons, on-time delivery

## How to use
Open `index.html` in any browser (Chrome recommended). That's it.

All data is saved in the browser's local storage on the computer you use it on.

## Hosting on GitHub Pages (optional)
Repo → Settings → Pages → Source: `main` branch, root folder → Save.
The app will be live at `https://<username>.github.io/<repo-name>/`.

## Notes
- Data is stored per browser, per computer. Take PDF copies of invoices as your permanent records.
- Clearing browser data will erase saved customers/invoices — export PDFs regularly.
