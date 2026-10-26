# Vinod Lead Manager

A lightweight outbound lead tracker in a single HTML file. No install, no server, no sign-up. Open `index.html` in a browser and start adding leads.

## Why I built it
Running cold email and LinkedIn outreach means juggling Apollo exports, sequence tools and spreadsheets. Leads that reply or need a follow-up get lost between them. A full CRM is overkill for a solo marketer or a small team. This app sits in the gap: one page to see every active lead, what stage it's at, and who needs a nudge today.

## Use cases
- **Daily follow-up list.** Open the app, click "Due now", and work through overdue and today's follow-ups first.
- **Tracking replies from cold email.** Move a lead from Contacted to Replied to Meeting as conversations progress, with notes on what was said.
- **Working an Apollo list.** Export a filtered list from Apollo, import the CSV, and duplicates are skipped automatically.
- **Signal-based prospecting.** Log the trigger (hiring, funding, new tech) in notes so every follow-up references a real reason to reach out.
- **Weekly reporting.** Pipeline counts show at a glance how many leads sit in each stage. Copy the CSV into Google Sheets for a report.
- **Event or LinkedIn leads.** Quick-add contacts met at events or on LinkedIn, then set a follow-up date before they go cold.

Who it's for: SDRs, founders doing their own outbound, freelancers and small agencies who want a pipeline view without paying for a CRM.

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

## Live app
https://joshivinod475-sudo.github.io/Lead-Manager/

## How to use
1. Download `index.html` (or clone the repo).
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
