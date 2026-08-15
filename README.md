# Intern Performance KPI Tracking System

## Objective
Evaluate and track intern performance through a metrics-based system.

## KPI Design
- **Task Completion Time** — Average days to complete assigned tasks (lower = better)
- **Project Quality Score** — Mentor-rated score, scale 1-10 (higher = better)
- **Mentor Feedback Score** — Mentor-rated score, scale 1-5 (higher = better)
- **Overall Score** = 30% Completion Time + 40% Quality + 30% Mentor Feedback

## Project Summary
Built an automated system in Python (pandas) to calculate intern performance 
scores monthly, generate supervisor-ready reports, and flag top performers 
and interns needing additional support.

## Key Insights
- Completion time improved in February (4.52 days avg) vs January (6.21 days avg)
- Quality scores dipped slightly by March
- Zainab Yousaf, Bilal Hussain, and Zainab Butt were top performers across 
  different months
- Hina Riaz and Sara Ahmed appeared multiple times in the "needs support" 
  category, suggesting a need for additional mentor attention

## Tools Used
Excel (data prep), Google Colab, Python, pandas

## Files
- `intern_kpi_data.csv` — raw KPI dataset
- `intern_kpi_scored_data.csv` — dataset with individual calculated scores
- `monthly_kpi_report.csv` — automated monthly summary report
- `intern_kpi_scored.ipynb` — notebook with code and analysis
