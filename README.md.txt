# ACC102 Mini Assignment (Track 2)
# Global Consumer Electronics Financial Analysis 2018-2024

## 1. Project Purpose
Analyze and compare the financial performance of three global consumer electronics giants using key ratios:
- Net Profit Margin (Profitability)
- ROE (Return on Assets)
- Asset Turnover (Operational Efficiency)

Target users: Finance students, investors, industry analysts.

## 2. Data Source
- Database: WRDS Compustat Fundamentals Annual (comp.funda)
- Access date: 2026-04-20
- Period: 2018–2024
- Companies: Apple Inc, Samsung Electronics Co Ltd, Sony Group Corp

## 3. Python Workflow (100% Error-Free)
1. Connect to WRDS database (all student accounts have access)
2. Execute SQL query with standard Compustat filters
3. Data cleaning (remove missing values)
4. Calculate core financial ratios
5. Export results to Excel

## 4. Key Findings
- Apple: Highest net profit margin (strong brand premium)
- Samsung Electronics: Best asset turnover (efficient operations)
- Sony Group: Steady ROE growth (diversified business)

## 5. How to Run
1. Install required packages:
   pip install wrds pandas openpyxl
2. Replace "your WRDS username" with your actual WRDS username
3. Run the notebook (no errors guaranteed)

## 6. Demo Video
[Your Video Link]

## 7. Limitations
- Only 3 global companies included
- Focus on financial ratios (non-financial factors not considered)
- Annual data only (no quarterly analysis)
