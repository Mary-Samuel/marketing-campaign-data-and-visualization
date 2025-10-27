# Power BI Marketing Performance Dashboard

This Power BI project analyzes multi-channel marketing campaign performance, tracking key metrics and ROI to guide data-driven decisions.

## Project Objective
As a data analyst in a digital marketing team, the goal was to create a **fully interactive Power BI dashboard** that monitors campaign performance across multiple marketing channels.

The dashboard:
- Displays key marketing KPIs (Ad Spend, Impressions, Clicks, Conversions, Revenue, ROI)
- Allows exploration by **channel, product, category, and date**
- Provides **clear visuals** to support optimization strategies

## Tools & Skills Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Cleaning & Modeling
- Interactive Visual Design

## Key Measures (DAX)
```DAX
CTR = DIVIDE([Total Clicks], [Total Impressions], 0)
Conversion Rate = DIVIDE([Total Conversions], [Total Clicks], 0)
ROI = DIVIDE(([Total Revenue] - [Total Ad Spend]), [Total Ad Spend], 0)
