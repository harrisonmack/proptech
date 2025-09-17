# Proptech & Built World Funding — Reproducibility

This directory contains cleaned data, summary tables, figures, and a minimal manifest to verify outputs.

## How to Re-run

1. Place the source Excel file at the path set in Section 1 (`CONFIG["excel_file_path"]`), or update that path. Please get in touch with me directly for access to raw csv data. 
2. Run the notebook top to bottom:
   - Section 1: Setup & Config
   - Section 2: Data Ingest & Schema Check
   - Section 3: Cleaning Pipeline
   - Section 3.A: Investor Attribution
   - Section 4: Descriptive Summary
   - Section 5: Visualizations
   - Section 6: Trend & Insight Pass
   - Section 7: Sanity Checks & Reproducibility

## Notes

- Sectors are normalized to a canonical taxonomy (Multifamily → Residential; Fulfillment/Delivery → Logistics; Parking/Access Control → Commercial; finance-related sectors → FinTech).
- Investor attribution splits round capital equally across listed lead investors after cleaning aliases and removing placeholders.
- "Lead Investors" is a catch-all for all investors who participated in venture rounds -- true leads are not distinguished in this analysis.
