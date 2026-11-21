# SEC S7-2026-15 — Public comment letter tracker

**Live dashboard: <https://heatvent.github.io/sec-s7-2026-15-tracker/>**

Tracks public comment letters submitted on the SEC's proposed rule **S7-2026-15** (Optional Semiannual Reporting by Public Companies): who wrote in, whether they support or oppose the proposal, and why.

## What the dashboard shows

- **Total / Oppose / Support / Conditional** stat cards with percentages
- **Letters per day** — stacked bar by stance
- **Stance totals** — horizontal bar with percentages
- **Longest letters** — top 5 by word count, useful for finding substantive submissions
- **All letters** — sortable, searchable table, each row linking to the letter on sec.gov

## Files

- `index.html` — the dashboard. Self-contained (data is baked in, Chart.js from a CDN), no build step. Open it locally in a browser to test.
- `data.json` — the same letter data as plain JSON, for reuse or future automation.

## Updating

Regenerate `index.html` and `data.json` from the comment-letter pipeline, commit both, and push to `main`. GitHub Pages redeploys automatically.

## Source

Letters: <https://www.sec.gov/rules-regulations/public-comments/s7-2026-15>
Data last updated: 2026-05-09
