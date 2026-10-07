# DATA//GUARD
Data Quality Detective: Automated Data Quality & Validation Platform

## Assumptions
- Dates use DD/MM/YYYY (day-first). `07/10/2026` = 7 October 2026.
- Prices are in INR (₹).
- `order_id` is the unique key. `customer_id` may repeat (one customer, many orders).
- Data is generated with a fixed random seed (42) so results are reproducible.
- Each corrupted row has only one corruption (no overlap in V1).
