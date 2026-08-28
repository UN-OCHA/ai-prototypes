# FTS Total Funding 2026 Replica

A standalone rebuild of UN OCHA's [Total reported funding 2026](https://fts.unocha.org/global-funding/countries/2026) page from the Financial Tracking Service (FTS).

**Live page:** https://jayasekhon.github.io/FTS-Total-Funding-2026-Page/

Built to see how fast AI coding tools could replicate these sorts of webpages.

## What it does

Displays 2026 humanitarian funding by location, matching the layout, sorting, and filtering of the original FTS page:

- Sortable table of funding and pledges by location
- Location filter panel
- Source/destination organisation, org type, org level, sector, and flow status filter panels
- Totals summary (total incoming funding, total pledges)

It also includes per country funding summaries and functional navigation buttons to other placeholder pages.

## Data

Funding figures are a static snapshot of 2026 location-level data from FTS, embedded directly in the page. Filter panels without a corresponding data dimension in that snapshot (organisation names, sectors, flow status counts) are populated with representative sample values and labelled as such in the UI.

## Stack

Single self-contained `index.html` — vanilla HTML, CSS, and JavaScript, no build step, no server, no external dependencies. Hosted on GitHub Pages.
