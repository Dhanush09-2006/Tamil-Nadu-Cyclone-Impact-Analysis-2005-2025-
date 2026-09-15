# Tamil Nadu Cyclone Impact Analysis (2005–2025)

## Overview
This project analyzes cyclones that hit Tamil Nadu between 2005 and 2025, 
studying patterns in fatalities and economic damage using Python.

## Dataset
16-record dataset containing cyclone name, year, fatalities, and damage 
information. Raw data had inconsistent text formatting (e.g., "~15 approx"), 
which was cleaned into structured numerical columns.

## Tools Used
- Python
- Pandas (data cleaning & analysis)
- Matplotlib (visualization)

## Key Findings
- **Deadliest cyclone:** Ockhi (2017) — 245 deaths
- **Costliest cyclone:** Vardah (2016) — $3.38 billion damage
- **Correlation between fatalities and damage:** -0.066 (near zero, 
  indicating the two factors are largely independent)

## Visualizations
- Bar chart: Fatalities by cyclone
- Bar chart: Top 5 deadliest and costliest cyclones
- Scatter plot: Fatalities vs Damage relationship

## Conclusion
The analysis shows that cyclone fatalities and economic damage do not 
strongly correlate — a cyclone with low death toll can still cause 
massive property damage, and vice versa.
