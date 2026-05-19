# Canada Federal Grants Dashboard

[![Live Demo](https://img.shields.io/badge/Live%20Demo-anshdhawann.github.io-blue?style=for-the-badge&logo=github)](https://anshdhawann.github.io/canada-grants-dashboard/)

Interactive dashboard analyzing Canadian federal grants and contributions data (2004–2027). Built with Chart.js, runs entirely in the browser — no server required.

## Dataset

- **670,735** grant/contribution records
- **$569B** total value
- **396,483** unique recipients
- Source: [Government of Canada Grants & Contributions Open Data](https://search.open.canada.ca/grants/)

## Features

- **7 interactive charts**: Yearly trends, top programs, value distribution, top cities, recipient types, federal departments, industry split
- **Sidebar filters**: Year range, province, value range, recipient type, program search
- **Sortable tables**: Top grants by value, top companies by total value
- **Data-derived industry mapping**: Programs auto-categorized into Clean Tech, Energy, Health, R&D/Innovation, Agriculture, Infrastructure, and more

## Usage

**Live:** [anshdhawann.github.io/canada-grants-dashboard/](https://anshdhawann.github.io/canada-grants-dashboard/)

**Locally:** Open `index.html` in any browser. All data is pre-loaded — no backend, no API keys, no network calls (after initial page load).

## Files

| File | Size | Description |
|------|------|-------------|
| `index.html` | 31 KB | Dashboard HTML + JS + CSS |
| `data.js` | 2.4 MB | Pre-processed grant data (670K records) |

## How it works

The raw CSV exports from Canada's open data portal were pre-processed into aggregated JSON (program/year/province/city/recipient-type counts and top 2,000 grants). This data is embedded in `data.js` and rendered by Chart.js in the browser.

## License

Data sourced from the Government of Canada Open Government Portal. Dashboard code is MIT.
