# Fund monitor

A single-page monitor for a simulated global equity fund, hosted so a small team
can read the same thing without passing files around.

- **[Open the monitor](https://tiscode.github.io/weekly-brief-3016dd/)** — where we stand,
  the trades to place this week, the cut loss and take profit level on every line, and the
  factor scores behind each call. Click any line in the book for its investment thesis.
  `detail.html` serves the same page, for older links.
- **[26 August brief](https://tiscode.github.io/weekly-brief-3016dd/brief.html)** — the
  previous weekly brief, kept for the record. Out of date; do not trade from it.
- `working-papers/` — the same numbers as plain text, for checking or pasting into slides.

Every page is self-contained HTML. No build step, no dependencies, no tracking. They
carry a `noindex` directive and the site carries a `robots.txt`, so they should stay out
of search results.

Figures are a simulation for a university course. Nothing here is investment advice.
