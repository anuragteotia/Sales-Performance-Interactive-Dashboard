# Executive Sales Performance Dashboard 

## 📌 Project Overview
This was my first project developed during the Data Analytics learning. The core objective was to clean, link, and model a transactional dataset containing 999+ rows and 25 relational fields across separate data buckets (`Orders`, `Returns`, and `People`) into a single unified business platform.

## 🛠️ Key Analytical Steps Performed
1. **Data Joining & Integrity:** Leveraged programmatic logic to evaluate returned transactions against master orders by building an automated tracking link column (`=XLOOKUP(B2, Returns!B:B, Returns!B:B, "No")`) to completely neutralize gross margin errors.
2. **Backend Framework Architecture:** Constructed 4 multi-dimensional Pivot Tables to safely segment core operational metrics without duplicating master database rows.
3. **Interactive Control Integration:** Implemented fully synchronized visual cross-filtering Slicers mapped to systemic report connections across line, bar, and category breakdowns.

## 📊 Dashboard Focus Metrics
- **Total Net Revenue:** Live dynamic scoreboard filtering out system returns.
- **Sales Share by Category:** Segmented breakdown using contribution mapping charts.
- **Yearly Sales Growth Trends:** Rolling longitudinal time-series chart showing operational expansion metrics.
- **Department-wise Revenue:** Symmetrical performance layout tracking structural business units.

## 🖼️ Dashboard Preview

<img width="1000" height="621" alt="image" src="https://github.com/user-attachments/assets/571d02d9-3058-420d-b4a0-863d3b19d1f4" />

