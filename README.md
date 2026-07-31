# HF Model & Benchmark Matrix

Self-contained, wiki-style dashboard of every major Hugging Face model + variant
from the last 365 days, benchmark scores, quant/VRAM sizes, and discussions.

Data scraped from Hugging Face. This dashboard is a single static `index.html`
(no external requests, no build step) — served via GitHub Pages.

## Pages
Open the site at the GitHub Pages URL (see repo settings → Pages, or the link
in the sidebar once enabled).

## Source
Pipeline lives in `huggingface-data/` in the source tree:
`scrape → fetch cards → link → extract scores → estimate VRAM → discussions → matrix → dashboard`.

Counts (last build): 1,197 providers · 6,481 root models · 10,619 variants ·
80 benchmarks · 3,267 scores · 36,144 discussions.
