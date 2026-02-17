# London UC Surge: East London 'Corridor' Drives Highest Volume, but Pressure is System-Wide

### Project Overview
This project explores the regional distribution of Universal Credit (UC) caseload growth across London. The objective was to identify high-growth areas and determine if the recent surge in demand is concentrated in specific boroughs or distributed evenly across the capital.

### Methodology & Tech Stack
* **Data Source:** DWP Stat-Xplore (People on Universal Credit). Data Period: Jan 2024 – Jan 2025.
* **Python (Pandas):** Automated data ingestion from Stat-Xplore; performed data normalization and addressed geographic outliers (e.g., isolating the City of London as a low-resident demographic outlier to prevent skewing regional averages)
* **PowerBI:** Used for Visualization.

### Visual Analysis
![Recording 2026-02-17 173819](https://github.com/user-attachments/assets/0030af7e-8203-4ae0-9b97-397dfa90e627)
**Interactive Dashboard Demo**: *The GIF above demonstrates the Dynamic Headline feature (DAX), where the report title automatically updates to reflect specific borough-level surges when selected, providing instant, context-aware insights for policymakers*

### Analyst Insight
* **Total Growth:** London's UC caseload increased by +169,420 claimants (16.8% YoY)
* **Volume Drivers:** Just three boroughs (Tower Hamlets, Newham, Hackney) accounted for 18.4% of the entire city's growth
    1.  **Tower Hamlets:** +10,631 claims
    2.  **Newham:** +10,428 claims
    3.  **Hackney:** +10,151 claims

* **Distribution:** These top 3 boroughs account for 18.4% of the total growth, with the remaining ~82% distributed across the other 30 boroughs, indicating widespread demand.

### Technical Execution
**Analysis Environment:** Google Colab
**Key Libraries:** 'Pandas' (Data Manipulation), Datetime (Temporal Scaling)
**Reproducubility:** The Stat-Xplore Extraction Guide belown ensures analysis can be refreshed monthly as new DWP data is released

### Stat-Xplore Extraction Guide
**Table:** 'People on Universal Credit'  (This represents the "Caseload" or stock, which is the standard metric for "claims rising" over time. "Claims Made" is the flow of new applications).
Rows (Geography): -> National - Regional - LA - OA -> London
Columns (Time): The two distinct time points to calculate the "Rise" (January 2024 and January 2025) 

---
*Author: [Benjamin Mba]*
*LinkedIn: [linkedin.com/in/benjamin-mba-42a6bb14a]*
