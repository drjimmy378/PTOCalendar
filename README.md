[README.md](https://github.com/user-attachments/files/28065014/README.md)
# Help Desk PTO Calendar

A simple, browser-based team time-off calendar. No server or database required — just open the HTML file or host it on GitHub Pages.

## Features

- **Month & list views** with color-coded team members
- **Date range support** — add a full week off in one step, with skip-weekends option
- **Overlap warnings** — flags when multiple people are out the same day
- **Holiday tracking** — office holidays and early closures shown in tan
- **Settings panel** — add/remove team members and holidays without touching code
- **Export/import** — back up and restore all data as JSON
- **Zero dependencies** — single HTML file, runs in any browser

## Setup

1. Download `index.html` (or clone this repo)
2. Open it in a browser — that's it

To host for your team: enable GitHub Pages in repo Settings → Pages → deploy from `main` branch.

## Data Storage

All data is stored in your browser's localStorage. Each browser maintains its own copy. Use the **Export/Import** feature in Settings to share data between browsers.
