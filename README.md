# BKKIFF 2026 Planner

A single-file planner for the Bangkok International Film Festival, 13–27 September 2026: 115 titles, 167 screenings, 5 cinemas.

**Live page:** https://anulordlearnalot-ai.github.io/BKKIFF-2026/

## What it does

- Browse the programme by day (screenings grouped per cinema) or by film.
- Filter by cinema, collection (new films, Shōhei Imamura retrospective, Thai classics, shorts) or search by title, director or country.
- Tap **+** on any screening to add it to your plan.
- The plan flags overlapping screenings and transfers that are too tight, using adjustable gaps for Q&A time, same-cinema changeovers and trips to another cinema.
- Export the plan as a spreadsheet (.csv) or a printable page, or copy it as text.
- The **Awards** tab lists the 2026 jury results in full, and award-winning films carry a badge wherever they appear in the programme.

Your plan is stored in your own browser only — nothing is sent anywhere.

## Running it

`index.html` has no build step and no dependencies. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Poster images are pulled from IMDb when the file is opened directly in a browser; where they can't load, each film falls back to a designed title card.

## Source

Schedule taken from the official BKKIFF 2026 screening programme. Runtimes and film details cross-checked with Letterboxd and IMDb; descriptions are original summaries. Times can change — check the festival's own channels before you go.
