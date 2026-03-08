# Logistics & Delivery Performance (Olist Dataset) — Adura Datahub

## What this project answers
- What is the **on-time delivery rate**, and how does it change over time?
- How long do deliveries take (**delivery days**) and where do delays happen?
- Which states perform best/worst on **on-time rate, delivery speed, and freight cost**?
- What actions can improve delivery SLA and customer experience?

## Files in this repo
### Executive report (PDF)
- `outputs/adura_datahub_project2_olist_report.pdf`

### Visuals (PNG charts)
See `output/`:
- On-time rate trend (monthly)
- Avg delivery days trend (monthly)
- On-time rate by top states
- Avg delivery days by top states
- Avg freight by top states
- Delay days distribution

### Dashboard workbook (Excel)
- `adura_datahub_project2_olist_dashboard.xlsx`

### Data
Due to GitHub upload limits, the repo includes a **representative sample + summaries** packaged as:
- `data/project2_data_small_pack.zip`

(Data source: Olist Brazilian E-commerce dataset on Kaggle.)

## KPI definitions
- **On-time**: delivered on or before the estimated delivery date
- **Delivery days**: purchase timestamp → customer delivery timestamp
- **Delay days**: delivered date − estimated date (positive means late)

## Recommendations
1) Monitor on-time weekly by state and volume to prioritize intervention.
2) Improve slow lanes by reducing carrier-to-customer time.
3) Track freight per order and flag high-cost, slow-delivery areas.
