# Supermarket Sales Analysis Dashboard

An interactive Excel dashboard that analyses supermarket sales data to compare product categories and outlets, explore sales relationships and understand statistical patterns.

<img width="1095" height="447" alt="009k" src="https://github.com/user-attachments/assets/fed1195a-a1fa-41e3-b222-4985bc838e41" />


## Project Goal
Management had only a raw sales dataset, which made it hard to identify top-performing products, compare outlets and see sales patterns. This project turns that data into a clear dashboard.

## Dataset
- 8,523 records from the BlinkIT Grocery Data sheet
- Fields: item type, fat content, item visibility, outlet identifier, outlet type, location tier, sales and rating
- Data cleaning: inconsistent fat content labels (LF, low fat, reg) were standardised into Low Fat and Regular

## Tools Used
- Microsoft Excel
- Pivot tables and pivot charts
- Slicers for interactive filtering
- Formulas (SUM, AVERAGE, MEDIAN, STDEV, QUARTILE, PERCENTILE, CORREL)

## Analysis Objectives
1. **Overall sales performance:** total sales, average sales per record, average product visibility
2. **Product category comparison:** top four categories vs the rest, highest and lowest categories, sales by outlet type
3. **Outlet performance and relationships:** Low Fat vs Regular by outlet, visibility vs sales, category contribution by outlet type
4. **Statistical analysis:** average, median, min and max, variation, unusual sales values, averages by category, outlet type and location

## Key Findings
- Total sales are about 1.20 million, with an average of 141.0 per record.
- The top four categories (Fruits and Vegetables, Snack Foods, Household, Frozen Foods) contribute 50.6% of sales.
- Low Fat products account for about 65% of sales at every outlet.
- The two Grocery Stores sell about 40% less than the supermarkets.
- Item visibility has no relationship with sales (correlation of -0.001).
- Average sales per record are almost identical across outlet types and locations, and vary most by product category (126 to 149).
- Sales vary moderately (standard deviation of 62.3, or 44% of the mean), and there are no statistical outliers.


