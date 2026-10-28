# 3marketeer

Website for **3marketeer**, a full-service B2B marketing studio: strategy, creative and growth systems.

Live at **https://3marketeer.com**

## Contents
| Path | What it is |
|---|---|
| `/` (`index.html`) | 3marketeer company website |
| `/leads/` (`leads/index.html`) | Vinod Lead Manager, an outbound lead tracker |
| `CNAME` | Custom domain for GitHub Pages (`3marketeer.com`) |

## Website
Single-page site, plain HTML, CSS and JavaScript with no build step. Fonts from Google Fonts (Cormorant Garamond, Jost, DM Mono).

Sections: hero, services (Strategy, Creative, Systems), outbound spec, process, engagement models, tool stack, FAQ and contact.

To edit: change `index.html` and push to `main`. GitHub Pages redeploys in about a minute.

## Lead Manager
A lightweight outbound lead tracker at **https://3marketeer.com/leads/**.

- Pipeline stages: New, Contacted, Replied, Meeting, Won, Lost
- Follow-up dates with overdue and due-today flags
- Search, sort, edit and duplicate warnings
- CSV import (works with Apollo exports) and CSV export for Google Sheets
- Data stays in your browser's localStorage. Export a CSV regularly as a backup.

## Author
Vinod Joshi
