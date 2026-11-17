# Callsign Trainer

**English** · [Nederlands](#nederlands)

A Duolingo-style trainer for aircraft **ICAO designators ↔ radio callsigns** (e.g. `RYR` = *Ryanair*). One self-contained HTML file: no server, no account, no install.

**Open the app:** https://jasper-acc.github.io/callsign-trainer/

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

---

# Nederlands

Een leerapp in Duolingo-stijl voor **ICAO-codes ↔ roepnamen (callsigns)** van vliegtuigmaatschappijen (bv. `RYR` = *Ryanair*). Eén enkel HTML-bestand: geen server, geen account, geen installatie.

**Open de app:** https://jasper-acc.github.io/callsign-trainer/

> The app interface itself is in English.

## Functies
- 443 ingebouwde callsigns, met maatschappij en land in de bibliotheek (niet in de quiz)
- Drie vraagtypes: code → callsign, callsign → code, luisteren → code
- Antwoord typen of uitspreken (NATO-alfabet wordt herkend), of meerkeuze
- Herhaling: moeilijke callsigns komen vaker terug; nieuwe komen geleidelijk
- Statistieken: gekende callsigns, nauwkeurigheid, XP
- Eigen callsigns toevoegen; gebruik `/` om meerdere geldige callsigns te scheiden
- Import uit CSV, Excel (.xlsx) of een Google Sheets-link; export naar .xlsx, CSV, klembord of JSON-back-up
- Codes worden altijd in hoofdletters ingevuld

## Gebruiken
- **Gsm / tablet / computer:** open de link hierboven in een browser; op gsm kan je "Toevoegen aan startscherm" gebruiken.
- **Offline:** bewaar `index.html` en open het in een browser.
- **Spraak** werkt het best in Chrome of Edge.

## Je gegevens
Alles wordt lokaal in je browser bewaard (`localStorage`); er wordt niets verstuurd. Voortgang geldt per browser en per toestel; verplaats ze met de JSON-back-up in de bibliotheek. Browsergegevens wissen wist ook je voortgang.

## Bronnen en kanttekeningen
De callsigns komen uit een persoonlijke lijst. Maatschappijnamen en landen komen uit openbare datasets (vradar standing-data, OpenFlights) en zijn niet officieel; sommige ontbreken of zijn verouderd.
