# SaaS-Scenario-Model# SaaS Scenario Modeling (Google Sheets Version)

📄 [View Google Sheet](https://docs.google.com/spreadsheets/d/1YzBiY5HyLAGPYOcRIxekCUXlO0zhs7EHT5NTuG_YwvY/edit?usp=sharing)

---

This project models SaaS unit economics across three business scenarios: Base, Best Case, and Worst Case. Built entirely in Google Sheets, it lets users toggle between scenarios using a dropdown and see how core metrics update automatically.

## Initial Scenario Assumptions

| Metric                   | Base      | Best Case | Worst Case |
|--------------------------|-----------|-----------|------------|
| ARPU                     | $200      | $250      | $150       |
| Gross Margin %           | 80%       | 85%       | 70%        |
| Customer Lifetime (mo)   | 24        | 30        | 18         |
| CAC                      | $200      | $180      | $250       |
| New Customers / Month    | 250       | 300       | 150        |
| Fixed Costs / Month      | $40,000   | $35,000   | $45,000    |

Dropdown cell in the sheet allows users to switch between these scenarios and recalculate in real-time using `CHOOSE()` and `MATCH()` logic.

## Output Metrics

- Monthly Revenue
- Gross Profit
- CAC Spend
- Monthly Burn
- Net Cash Flow
- Customer Lifetime Value (LTV)
- LTV:CAC Ratio
- Payback Period

## Purpose

To demonstrate a manual, spreadsheet-based approach to scenario modeling for SaaS finance. Useful for hands-on planning and educational walkthroughs without requiring code or tools beyond Google Sheets.

## Features

- Scenario selection via dropdown
- Auto-updating calculations using dynamic cell references
- Optional chart for cash flow visualization

## Author

Tim Pham  
[LinkedIn →](https://www.linkedin.com/in/timphamtx)
