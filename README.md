# Healthcare Claims – Power BI

Power BI report demonstrating claims analytics across overview, provider financials, and backlog/SLA risk.

## What’s included
- **/pbix/**: Healthcare_Claims_Keerthana.pbix
- **/screenshots/**: 
  - 01 – Claims Overview
  - 02 – Provider & Financials
  - 03 – Aging & SLA (Pending Backlog)
  - 04 – Filters in Action (Provider = Northside Pediatrics, Aging Bucket = 30+)
- **/data/**: Sample claims dataset (optional)

## Highlights
- Marked **Date** table; KPIs implemented as **measures** (Total/Avg Amount, Total Claims, Approval%/Denied%, MoM%).
- Backlog logic via **Pending Days** + **Aging Bucket (15–30d, 30d+)** and breach measures (>14/>30 days).
- Chart→table **cross-filtering**, continuous date axes, and conditional formatting for readability.

## How to open
- Power BI Desktop → Open `/pbix/Healthcare_Claims_Keerthana.pbix`.
