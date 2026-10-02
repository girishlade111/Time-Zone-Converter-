# Time Zone Converter

A fast, single-page time zone converter that converts a date/time from a source time zone to multiple destination time zones at once — ideal for scheduling meetings across cities and countries.

## Features

- Convert one source date/time into **multiple destination time zones** simultaneously
- **moment-timezone** bundled with full IANA timezone data
- One-click **swap** between source and first destination zone
- **Set current time** instantly for live "what time is it there" checks
- **Save named zone sets** (e.g. "Work Team") for quick reuse
- **Copy formatted result** (e.g. `2026-10-03 14:30:00 PDT (-07:00)`) to clipboard
- Remove individual destination zones from the results
- Fully client-side — no backend, no build step, works offline after first load (except CDN scripts)

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- [moment.js](https://momentjs.com/) + [moment-timezone](https://momentjs.com/timezone/) via CDN

## Quick Start

Just open `index.html` in any browser, or serve the folder with any static server:

```bash
npx serve .
```

## Deploy

Static site — served via GitHub Pages directly from the `main` branch.

---

Built by Girish Lade · https://ladestack.in
