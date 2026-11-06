# Car Comparison Table — Pakistan (Web)

A single-page car comparison tool for popular cars sold in Pakistan.
Pick up to 3 cars and compare them side by side:

- Price (indicative PKR), engine, power, mileage, transmission, fuel, body type, seats, airbags, boot space
- The best value in each comparable row is highlighted with a green ★
- A short "quick take" verdict: cheapest, best mileage, most power, best all-rounder

Default comparison: Suzuki Alto AGS vs Toyota Yaris ATIV CVT vs Honda Civic Oriel.

## How to use

1. Open `index.html` in any modern browser (double-click the file, or serve the
   folder with any static server).
2. Tick / untick cars in the picker — the table updates instantly.

No build step, no dependencies, no data leaves your browser.

## Price note

Prices shown are **indicative ex-showroom estimates, rounded, as of November
2026 — NOT live prices**. Actual prices change with taxes, dealer charges and
model-year updates, so always confirm with an authorised dealer before buying.
Mileage figures are approximate manufacturer/owner-reported averages.

## What was practiced

- Single self-contained HTML/CSS/JS page
- Data-driven rendering: a cars array + a rows definition drive the whole table
- "Best in row" logic (lowest price, highest mileage/power/airbags) with ties handled
- Sticky table header, responsive horizontal scroll, accessible checkboxes
