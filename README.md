# Power BI Sales Performance Analysis (Supermarket Dataset)

Built an end-to-end sales performance analysis project in Power BI with a strong focus on data cleaning, financial metric reconstruction, and root-cause diagnostics (not just visuals).

## Key insight
February sales decline was driven mainly by fewer transactions (demand drop), while average spend per transaction stayed relatively stable — indicating a demand-driven dip rather than pricing issues.

## What I built
- Power Query cleaning & standardization
- Reconstructed metrics: Sales, COGS, Gross Profit, Gross Margin %
- Star Schema modeling + validated relationships
- DAX measures for MoM analysis and contribution logic
- Root Cause page (Matrix + Table) with two Tooltips:
  - Tooltip – Root Cause (Matrix)
  - Tooltip – Root Cause (Table)

## Report pages
- Overview
- Product Line
- Branch and City
- Root Cause
- Tooltip – Root Cause (Matrix)
- Tooltip – Root Cause (Table)

## Screenshots

### 1) Overview (KPIs + Q1 trend)
![Overview](screenshots/overview.png)

### 2) Data model (Star schema)
![Data model](screenshots/data-model.png)

### 3) Product Line Drivers (Feb vs Jan)
![Product line drivers](screenshots/Product%20Line%20Drivers%20%E2%80%94%20February%20MoM%20Drop%20(Feb%20vs%20Jan).png)

### 4) Root Cause (Overall worst context)
![Root cause overall](screenshots/root-cause-overall.png)

### 5) Root Cause (Selected cell + drill table)
![Root cause selected cell](screenshots/root-cause-selected-cell.png)

### 6) Tooltip – Root Cause (Matrix)
![Tooltip matrix](screenshots/tooltip-matrix.png)

### 7) Tooltip – Root Cause (Table)
![Tooltip table](screenshots/tooltip-table.png)

## Files
- `pbix/Sales Analysis.pbix`
- `data/SuperMarket Analysis.csv`
- `screenshots/` (project images)
