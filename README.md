# Beverage Retailer Sales Dashboard (Excel)

An Excel dashboard built to analyze beverage retailer sales data across different regions of the USA.

Note: This is a practice dataset used for learning purposes. It is not affiliated with or endorsed by any real company or brand.

## Project Overview

This project takes raw sales data and turns it into a dashboard that's easy to read and filter. Everything is done in Excel using PivotTables, Slicers, and Charts, without using Power BI or SQL.

## Project Structure

### Data Sheet
The raw dataset with over 9,000 rows, containing:
- Retailer, Retailer ID, Invoice Date
- Region, State, City
- Beverage Brand (Coca-Cola, Sprite, Fanta, Diet Coke, Powerade, Dasani Water)
- Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin

### Analyze Sheet
Built using PivotTables to summarize the data:
- Total Sales, Units Sold, Average Price per Unit, Total Operating Profit
- Sales by Brand, split by Year (2024 vs 2025)
- Sales and Operating Margin by Quarter

### Dashboard Sheet
- Region and Year slicers to filter the dashboard
- KPI cards for Total Sales, Units Sold, Average Price, and Total Operating Profit
- Sales and Variance
