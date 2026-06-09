# FIFA World Cup 2026 — Match Tracker

A lightweight, mobile-first web app for following the **FIFA World Cup 2026**
(Canada · Mexico · USA, 11 Jun – 19 Jul, 104 matches). Browse the full schedule,
see live scores, follow your favourite teams, and add fixtures to your calendar.

**🔗 Live site:** https://ahmedco88.github.io/Fifa2026/

## Features

- **Full schedule & scores** — all 104 matches grouped by day, with live scores and
  final results as games are played.
- **Your local timezone** — kick-off times are auto-converted to the viewer's own
  timezone, with the matching label (e.g. `AEST`, `GMT+10`, `PST`).
- **Live local clock** — a ticking current-time line in the header.
- **Match states** — `Upcoming` (with kick-off time), `● Live`, or `FT` with the score.
- **Auto-refresh** — scores update automatically while any match is live (no manual tap).
- **Filters** — by group, "My teams only", and "Upcoming only".
- **Favourite teams** — pick the teams you follow; saved in your browser (`localStorage`).
- **Country flags** — real national flags for every team.
- **Jump to today** — scroll straight to today's (or the next) matches.
- **Add to calendar** — download an `.ics` file for any fixture.

## Tech

- A single self-contained `index.html` — plain HTML, CSS, and vanilla JavaScript.
- No build step, no dependencies, no framework.
- Match data from the open-source [openfootball](https://github.com/openfootball/worldcup.json)
  dataset; flags from [flagcdn](https://flagcdn.com).

## Running locally

It's a static page — just open `index.html` in any browser (an internet connection
is needed to fetch the schedule and flags).

## Deployment

Hosted on **GitHub Pages**, served from the `main` branch.

## Notes

- Times are converted from each venue's local kick-off; scores may lag a few minutes
  behind the live broadcast as the dataset updates.

## Credits

Designed by [Ahmed Al-Obaidi](https://www.linkedin.com/in/drobaidi).
