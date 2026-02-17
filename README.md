# London UC Surge: East London 'Corridor' Drives Highest Volume, but Pressure is System-Wide

### 🚀 Project Overview
1. Project Overview: This project explores the regional distribution of Universal Credit (UC) caseload growth across London. The objective was to identify high-growth areas and determine if the recent surge in demand is concentrated in specific boroughs or distributed evenly across the capital.

### 🛠️ Methodology & Tech Stack
* **Data Source:** Source: DWP Stat-Xplore (People on Universal Credit). Data Period: Jan 2024 – Jan 2025.
* **Python (Pandas):** Used for data cleaning, calculating "Absolute Change," and ranking boroughs by volume.
* **PowerBI:** Used for Visualization.

### 📉 Visual Analysis
![Recording 2026-02-17 173819](https://github.com/user-attachments/assets/0030af7e-8203-4ae0-9b97-397dfa90e627)


### 🔍 Analyst Insight
* **Total Growth:** London's UC caseload increased by +169,420 claimants (16.8% YoY)
* **Volume Drivers:** The analysis identified an "East London" cluster driving the highest raw volume:
    1.  **Tower Hamlets:** +10,631 claims
    2.  **Newham:** +10,428 claims
    3.  **Hackney:** +10,151 claims
* **Distribution:** These top 3 boroughs account for 18.4% of the total growth, with the remaining ~82% distributed across the other 30 boroughs, indicating widespread demand.

### 💻 How to Run This Code
1.  Clone the repository.
2.  Install dependencies: `pip install pandas`
3.  Run the cleaning script: `London_Universal_Credit_Analysis.ipynb`

### Stat-Xplore Extraction Guide:
Table: 'People on Universal Credit'  (This represents the "Caseload" or stock, which is the standard metric for "claims rising" over time. "Claims Made" is the flow of new applications).
Rows (Geography): -> National - Regional - LA - OA -> London
Columns (Time): The two distinct time points to calculate the "Rise" (January 2024 and January 2025) 

---
*Author: [Benjamin Mba]*
*LinkedIn: [linkedin.com/in/benjamin-mba-42a6bb14a]*
