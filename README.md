## WindowPain — Overview

WindowPain is a browser-based tool for cross-checking assessments against the mega-checking window spreadsheets. It runs entirely on your own machine, so nothing is uploaded to a server. **No student data ever leaves your computer. No GDPR issues.**

It's a single HTML file, no installation: open it in a browser and go.

**Use it now:** [digitaldickinson.github.io/windowpains/windowpain.html](https://digitaldickinson.github.io/windowpains/windowpain.html)

**What it does:**

1. Load the Checking Window spreadsheet. Filter and search by department, academic year, year of study, unit, or student.  Export any filtered view as CSV.
2. Load a second file and cross-check its marks against the Checking Window for a chosen unit (and assessment component, if it has more than one). It flags matches, mismatches, and anyone missing from either file.

**Confidence colour (Green / Yellow / Red):** every matched row also gets a confidence rating, because a "Match" can still hide something worth a second look.

- **Green** — a clean, exact match, nothing unusual.
- **Yellow** — it matched, but only after the app made a judgement call: a resit mark overriding an earlier attempt, a duplicate row it had to pick between, a text-only comparison, or a match that only holds within your tolerance setting. Hover the badge to see which applied.
- **Red** — a mismatch, or missing from either file. Always needs a look.

As with anything to do with data and spreadsheets, it's worth a quick eyeball before trusting the results. 
