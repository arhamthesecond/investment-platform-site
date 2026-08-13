# Investment Intelligence Platform — Site

This repo holds only the **built static site** and **sanitized JSON data
exports** for the Investment Intelligence Platform. It is generated output,
not source — do not edit files here directly.

Source code, the SQLite database, and full research live in a private repo
(per the split-repo decision in `DECISIONS.md` DEC-012, in the private repo).
This repo exists so GitHub Pages can serve the site for free from a public
repo without exposing that source.

`data-exports/` mirrors what the site itself renders — every fundamentals
figure and valuation result traces to a source URL or a formula, same as
the site.
