# Vinod Lead Manager

A lightweight outbound lead tracker in a single HTML file. No install, no server, no sign-up. Open `Index.html` in a browser and start adding leads.

## Features
- Lead details: company, contact, title, email, stage, follow-up date, notes
- Pipeline stages: New, Contacted, Replied, Meeting, Won, Lost
- Pipeline strip with live counts per stage; click a stage to filter
- Follow-up tracking: overdue and due-today leads are flagged, with a "Due now" filter
- Search across company, contact, email and notes
- Sort by follow-up date, newest, or company name
- Edit leads in place and change stage straight from the list
- Duplicate warning when a company or email already exists
- CSV import (works with Apollo exports: Company, First Name, Last Name, Title, Email)
- CSV export by download or copy to clipboard, ready to paste into Google Sheets
- Light and dark mode, works on mobile
- Data stored in your browser's localStorage

## How to use
1. Download `Index.html` (or clone the repo).
2. Double-click the file to open it in Chrome, Edge or Firefox.
3. Add leads, or import a CSV.

Your leads stay in that browser only. Export a CSV regularly as a backup.

## CSV format
Header row with any of these columns:

```
company,contact,title,email,status,followUp,notes
```

`status` must be one of the six stages. `followUp` uses `YYYY-MM-DD`.

## Tech
HTML, CSS and vanilla JavaScript. No dependencies.

## Author
Vinod Joshi
