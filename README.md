# India Unemployment Rate Analysis (2020)

End-to-end data analysis project examining state-wise and zone-wise unemployment trends in India during 2020, with a focus on the COVID-19 lockdown impact.

## Problem Statement
Analyze how unemployment varied across Indian states and regions in 2020, identify which states were hit hardest by the COVID-19 lockdown, and recommend where employment safety-net policies should be prioritized.

## Dataset
- 267 monthly records across 27 states/UTs, Jan–Nov 2020
- Fields: State, Date, Unemployment Rate (%), Estimated Employed, Labour Participation Rate (%), Zone, coordinates
- Source: Centre for Monitoring Indian Economy (CMIE), via public dataset

## Tools Used
- **Python**: Pandas (cleaning, aggregation), Matplotlib/Seaborn (visualization)
- **Excel/Power BI**: Interactive dashboard with formulas and charts
- **Microsoft Word**: Executive summary report

## Key Findings
- National unemployment peaked at **23.24%** in May 2020 (vs ~9.2% pre-COVID baseline)
- **Haryana** and **Tripura** had the highest average unemployment (>25%)
- **Meghalaya**, **Assam**, **Gujarat** were least affected (<7%)
- **North zone** was hit hardest on average; **West zone** recovered fastest
- No strong correlation between labour participation rate and unemployment rate (-0.07), suggesting the spike was a supply-shock (forced closures), not a participation-driven trend

## Files
- `analysis.py` — full Python EDA and chart generation script
- `unemployment_cleaned.csv` — cleaned dataset
- `chart1-5_*.png` — visualizations (national trend, state comparison, zone comparison, correlation, heatmap)
- `India_Unemployment_Dashboard.xlsx` — Excel dashboard with dynamic formulas and charts (importable into Power BI)
- `India_Unemployment_Report.docx` — executive summary report with insights and policy recommendations

## How to Run
```bash
pip install pandas matplotlib seaborn openpyxl
python analysis.py
```

## Author
Harsh Pandey — [GitHub](https://github.com/HARSHPANDEY9756) | [LinkedIn](https://linkedin.com/in/harsh-pandey-395a10237)
README.md
Displaying README.md.
