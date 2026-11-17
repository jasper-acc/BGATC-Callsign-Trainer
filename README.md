# Callsign Trainer

BGATC presents you:
A Duolingo-style trainer for aircraft **ICAO designators ↔ radio callsigns** (e.g. `RYR` = *Ryanair*). One self-contained HTML file: no server, no account, no install.

**Open the app:** https://jasper-acc.github.io/BGATC-Callsign-Trainer/

## Features
- 443 built-in callsigns, with airline name and country shown in the Library (not in the quiz)
- Three question types: code → callsign, callsign → code, listening → code
- Answer by typing or by speaking (NATO alphabet understood), or multiple choice
- Spaced repetition: hard callsigns come back more often; new ones are introduced gradually
- Statistics: known callsigns, accuracy, XP
- Add your own callsigns; use `/` to separate multiple valid callsigns (e.g. `SPEEDBIRD / BEELINE`)
- Import from CSV, Excel (.xlsx) or a Google Sheets link; export to .xlsx, CSV, clipboard or JSON backup
- Code answers are always uppercase

## Use it
- **Phone / tablet / computer:** open the link above in a browser. On a phone you can use "Add to home screen".
- **Offline:** save `index.html` and open it in a browser.
- **Voice input** works best in Chrome or Edge (Web Speech API).

## Your data
Everything is stored locally in your browser (`localStorage`). Nothing is sent anywhere. Progress is per browser and per device; use the JSON backup in the Library to move it. Clearing browser data erases your progress.

## Data sources and caveats
Callsigns come from a personal list. Airline names and countries were matched from public datasets (vradar standing-data, OpenFlights) and are not official; some may be missing or outdated.

## Import format
Columns (header optional): `code`, `callsign`, `airline`, `country`. Delimiters `;`, `,` or tab are detected automatically. A Google Sheets link works if the sheet is shared as "anyone with the link"; otherwise download it as .xlsx and import the file.
