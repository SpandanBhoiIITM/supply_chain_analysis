# Supply Chain Correlation Analysis

**Author:** SPANDAN BHOI  
**Email:** 23f3002227@ds.study.iitm.ac.in  

## Project Description
This repository contains a correlation analysis of supplier performance metrics from 77 procurement transactions for a major automotive manufacturer. The analysis helps in understanding relationships among supply chain variables to support data-driven decisions in supplier selection, inventory planning, and cost optimization.

## Dataset Metrics
- **Supplier_Lead_Time:** Days from order placement to delivery
- **Inventory_Levels:** Current stock quantities (units)
- **Order_Frequency:** Number of orders placed per month
- **Delivery_Performance:** On-time delivery rate (%)
- **Cost_Per_Unit:** Unit cost in dollars ($)

## Files Included
1. **correlation.csv** - Contains the correlation matrix of the above metrics.
2. **heatmap.png** - Screenshot of the correlation matrix in Excel with conditional formatting (Red-White-Green palette, 400x400–512x512 pixels).

## Instructions
1. Open `correlation.csv` to view the numeric correlation values.
2. Refer to `heatmap.png` for a visual representation using Excel's Red-White-Green conditional formatting.
3. The correlation matrix was generated using Excel’s Data Analysis ToolPak (Data → Data Analysis → Correlation) with labels included.

## Notes
- Red indicates low correlation, White indicates moderate correlation, and Green indicates high correlation.
- This analysis helps identify key relationships between supplier performance variables for better operational decisions.

