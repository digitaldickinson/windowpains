## WindowPain — Overview

WindowPain is a browser-based tool for cross-checking assessments against the mega-checking window spreadsheets. It runs entirely on your own machine, so nothing is uploaded to a server. **No student data ever leaves your computer. No GDPR issues.**

It's a single HTML file, no installation: open it in a browser and go.

**Use it now:** [digitaldickinson.github.io/windowpains/windowpain.html](https://digitaldickinson.github.io/windowpains/windowpain.html)

**What it does:**

1. Load the Checking Window spreadsheet. Filter and search by department, academic year, year of study, programme curriculum, unit, board outcome, or student name/MMU ID — picking a department narrows the programme and unit lists down to that department's own ones.
2. Switch between three views of the filtered rows, and export whichever one is on screen as CSV:
   - **All assessment lines** — the raw data, one row per assessment component.
   - **One row per student** — one row per student per unit; click through to a popup with every component for that unit, sorted by attempt, so a resit's position relative to the first sit is obvious.
   - **Student profile (by programme)** — one row per student per programme (grouped so a student on two programmes at once doesn't get merged into one), with a popup listing every unit on that programme and its outcome, flagged (resit/fail) ones sorted first.
3. Load a second file and cross-check its marks against the Checking Window for a chosen unit (and assessment component, if it has more than one). It flags matches, mismatches, and anyone missing from either file.

**Confidence colour (Green / Yellow / Red):** every matched row also gets a confidence rating, because a "Match" can still hide something worth a second look.

- **Green** — a clean, exact match, nothing unusual.
- **Yellow** — it matched, but only after the app made a judgement call: a resit mark overriding an earlier attempt, a duplicate row it had to pick between, a text-only comparison, or a match that only holds within your tolerance setting. Hover the badge to see which applied.
- **Red** — a mismatch, or missing from either file. Always needs a look.

As with anything to do with data and spreadsheets, it's worth a quick eyeball before trusting the results. 
