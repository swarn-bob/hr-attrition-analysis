# hr-attrition-analysis
Python dashboard analysing attrition patterns across 300 employees — dept risk flags, satisfaction vs churn, and actionable HR findings in Excel.
What This Is
A complete employee attrition analysis built on a realistic 300-employee dataset. The project simulates the kind of people analytics work an HR Operations or HR Analyst would do — identifying which departments, tenure bands, and satisfaction levels are driving attrition, and translating that into actionable findings.
Built entirely in Python using pandas and openpyxl. Output is a fully formatted Excel dashboard, no BI tool required.

Key Findings (from the dataset)
InsightValueOverall attrition rate28.0% (industry avg: 18–22%)Highest attrition deptOperations — 38.3%Lowest attrition deptMarketing — 6.9%Early tenure (0–1 yr) attrition~48%Satisfaction score 1–2 attrition~62%Overtime workers attrition premium+12 percentage points

Files
project1-attrition-analysis/
├── data/
│   └── employee_data.csv          # 300-employee dataset (generated)
├── outputs/
│   └── HR_Attrition_Analysis_Swarnadwip.xlsx   # Final dashboard
├── generate_data_and_analysis.py  # Full script
└── README.md

How to Run
bashpip install pandas openpyxl
python3 generate_data_and_analysis.py
Output Excel file will appear in /outputs/.

What the Excel Contains

Dashboard sheet — KPI tiles (total employees, attrition rate, active headcount, avg satisfaction), department attrition table with risk flags (High/Medium/Low), satisfaction score vs attrition breakdown
Employee Data sheet — Full 300-row dataset with all attributes
Key Findings sheet — 6 colour-coded finding cards with plain-language recommendations


Skills Demonstrated

Python (pandas, openpyxl)
HR data analysis and interpretation
Attrition modelling with weighted probability logic
Dashboard design in Excel without pivot tables or macros
Translating data into HR recommendations
