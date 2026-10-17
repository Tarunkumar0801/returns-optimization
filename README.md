
# Post-Purchase Support Optimization — PLS Returns Project

## About This Project
A data-driven program management case study analyzing **5,000 product returns** across 5 regions to identify avoidable returns, quantify financial impact, and recommend cost-saving interventions for Amazon's Product Lifecycle Support (PLS) team.

## Key Findings
- **45.4%** of returns (2,272 cases) are avoidable — **Rs.12.68 Crore** revenue at risk
- **54.3%** of customers never contact support before returning
- **Live Chat** is the most effective channel (20.2% prevention rate)
- Current prevention rate is only **14.4%** — massive room for improvement
- Average CSAT score is **2.71/5** — critically low

## Tools and Skills Used
- **Python** (pandas, matplotlib, seaborn) — Data analysis and visualization
- **SQL** (SQLite) — Business queries and trend analysis
- **Power BI** — Interactive KPI dashboard with DAX measures
- **DMAIC Framework** — Lean Six Sigma process improvement methodology

## Project Structure

PLS_Returns_Project/
├── data/
│   ├── returns_dataset.xlsx
│   └── returns_dataset.csv
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_sql_analysis.ipynb
│   ├── 03_root_cause_analysis.ipynb
│   └── 04_recommendations.ipynb
├── dashboards/
│   └── returns_dashboard.pbix
├── reports/
│   ├── dmaic_framework.docx
│   └── executive_summary.docx
├── images/
│   ├── returns_by_category.png
│   ├── return_reasons.png
│   ├── avoidable_pie.png
│   ├── pareto_return_reasons.png
│   ├── category_reason_heatmap.png
│   ├── cost_savings_chart.png
│   └── dashboard_screenshot.png
└── README.md


## Analysis Highlights

### Pareto Analysis
Top 3 return reasons account for 63% of all returns:
1. Setup/Configuration Issues (863 cases)
2. Defective/DOA (648 cases)
3. Changed Mind (645 cases)

### Cost Savings Projections
| Scenario | Prevention Rate | Returns Saved | Revenue Saved |
|----------|----------------|---------------|---------------|
| Conservative | 25% | 568 | Rs.3.17 Crore |
| Moderate | 40% | 909 | Rs.5.07 Crore |
| Aggressive | 60% | 1,363 | Rs.7.61 Crore |

### 5 Recommended Interventions
1. Proactive push notifications with setup guides (within 24hrs of delivery)
2. In-app "Talk to Expert" Live Chat feature (Days 1-30 post-purchase)
3. Video troubleshooting library (25+ multilingual videos)
4. Brand partner escalation protocol for compatibility issues
5. Post-purchase check-in emails (Day 3 and Day 7)

## Dashboard Preview
<img width="658" height="376" alt="Screenshot 2026-10-17 201724" src="https://github.com/user-attachments/assets/40710eb2-1c67-4785-a9ed-b87b794307c0" />

## Notebooks Overview

### Notebook 01 — Data Exploration
- Loaded and cleaned 5,000 return records
- Calculated baseline KPIs (avoidable rate, CSAT, revenue at risk)
- Created visualizations: category bar chart, reasons bar chart, avoidable pie chart

### Notebook 02 — SQL Analysis
- Avoidable return rate by product category
- Support channel effectiveness comparison
- Revenue at risk by region
- Monthly return trends
- Top brands with highest avoidable returns

### Notebook 03 — Root Cause Analysis
- Pareto chart identifying the 80/20 split of return reasons
- Category vs Reason heatmap revealing problem hotspots
- Support vs No-Support outcome comparison
- Avoidable percentage ranking by return reason

### Notebook 04 — Recommendations
- Cost savings projections at 25%, 40%, 60% prevention rates
- Priority Action Matrix (high avoidable + low support contact = biggest opportunity)
- Revenue savings visualization across prevention scenarios

## Author
**Meher Tarun Kumar**
Quality Specialist — Product Lifecycle Support
