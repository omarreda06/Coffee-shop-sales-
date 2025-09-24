

# Coffee Shop Sales — Excel Analytics Project

An Excel-based analytics project that cleans, models, and visualizes real coffee shop sales data from Maven Analytics, delivering an interactive dashboard with actionable KPIs.

## Preview

![Dashboard Screenshot]("C:\Users\UTD\Videos\Desktop Screenshot 2025.08.05 - 14.38.53.45.png")

- Transform raw sales data into an analysis-ready model using Power Query.  
- Build Pivot Table analyses for core business KPIs.  
- Design an interactive dashboard with slicers and stable benchmark charts.  

## Features

- Data cleaning and shaping with Power Query (consistent schema, standardized fields).  
- Pivot Table model for revenue, products, branches, and time analysis.  
- KPI-focused dashboard with dynamic slicers.  
- Fixed benchmark visuals: Transactions by Hour and by Day of Week remain unchanged by slicers to provide stable reference baselines.  

## Data Model

- Branches: store locations for performance comparison.  
- Order Dates: full date hierarchy for trend analysis.  
- Products: item-level detail for performance ranking.  
- Revenue: total and breakdown measures across dimensions.  

## Key Analyses

- Total Revenue across time.  
- Most Selling Products by revenue.  
- Orders by Branch to compare locations.  
- Revenue by Category to understand mix and contribution.  

## Getting Started

1. Clone or download the repository.  
2. Open the Excel workbook and enable content if prompted.  
3. If source files are provided separately, update Power Query connections to the local data path.  
4. Refresh All to load the latest data.  

## How to Use the Dashboard

- Use slicers (Branch, Product, Date) to filter KPIs and charts.  
- Review Monthly Revenue and Product Performance for trends and top items.  
- Compare branches using Orders by Branch and Revenue by Category.  
- Use Transactions by Hour and by Day of Week as fixed benchmarks for general sales activity regardless of slicer filters.  

## Tools and Skills

- Microsoft Excel: Power Query, Pivot Tables, measures, slicers, dashboarding.  
- Data Visualization: KPI design, layout, and storytelling.  

## Assumptions and Notes

- Fixed benchmark charts are intentionally disconnected from slicers to maintain consistent reference points.  
- Data definitions are assumed to be consistent across branches and categories.  

## Roadmap

- Add profit/margin analysis if cost data becomes available.  
- Introduce customer segmentation if identifiers exist.  
- Automate source refresh paths for one-click updates.  

## Credits

- Dataset: Maven Analytics.  
- Learning path: Digital Egypt Pioneers Initiative (DEPI).  

## Author

- Analyst: Early-stage data analyst focusing on practical Excel analytics, clean workflows, and clear dashboards—actively improving toward professional-level practice.  

## License

- This project is shared for learning and portfolio purposes. Add a formal license (e.g., MIT) if redistribution or reuse is intended.
