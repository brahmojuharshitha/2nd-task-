# Task 2 — Data Visualization and Storytelling

## Project overview
This beginner-level project explores a sample Superstore-style sales dataset and communicates the results through charts and a short visual report.

## Dataset
- File: `Superstore_Sales.csv`
- Rows: 600
- Date range: 2024-01-04 to 2025-12-30
- Important fields: Order Date, Region, Segment, Category, Sub-Category, Sales, Quantity, Discount, Profit, Ship Mode.

**Important:** The dataset is synthetic (generated for practice). It is not real company data. Do not describe the results as actual Superstore/company performance.

## Visualizations included
1. Sales by product category — bar chart.
2. Monthly sales trend — line chart.
3. Sales share by region — pie chart.
4. Profit by product category — bar chart.
5. KPI summary — total sales, total profit, number of orders, and average discount.

## Key findings from this sample
- Highest sales category: Technology.
- Highest sales region: Central.
- Highest profit category: Technology.
- Highest sales month: December 2025.

See `Task2_Visual_Report.pdf` for the charts, summary, and recommendations.

## How to explore in Power BI Desktop
1. Open Power BI Desktop.
2. Select **Get data → Text/CSV** and choose `Superstore_Sales.csv`.
3. Select **Load**.
4. Add a clustered bar chart: Axis = Category, Values = Sales.
5. Add a line chart: X-axis = Order Date (use Month), Y-axis = Sales.
6. Add a pie chart: Legend = Region, Values = Sales.
7. Add a clustered column chart: Axis = Category, Values = Profit.
8. Add Card visuals for Sales (Sum), Profit (Sum), and Order ID (Distinct count).
9. Save your Power BI report as `Sales_Dashboard.pbix` if you build it in Power BI.

## Before submitting
- Open the PDF and check that it displays correctly.
- If your mentor specifically expects a Power BI dashboard, import the CSV and save your own `.pbix` file; this package does not contain a `.pbix` file.
- Read the charts and findings so you can explain what each one means.
- Add your name, internship details, and any changes you personally make.
