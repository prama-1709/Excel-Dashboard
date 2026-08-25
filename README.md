# Excel-Dashboard
Interactive Commercial Performance Dashboard

#  Commercial Performance Dashboard

##  Project Overview

The **Commercial Performance Dashboard** is a data analysis and visualization project created to analyze the sales performance of **Alhat Groups and Company**.

The dashboard converts sales data into an interactive and easy-to-understand report. It provides information about **total sales, quantity sold, total amount, discounts, regional sales, monthly quantity, yearly sales, and regional discounts**.

The main goal of this project is to help management understand sales performance and make better business decisions using data.

#  Purpose of the Project

The main purpose of this project is to provide a simple visual view of the company's commercial performance.

It helps answer questions such as:

* What are the total sales?
* How many products were sold?
* What is the total sales amount?
* How much discount was given?
* Which region has the highest sales?
* Which year had the highest sales?
* Which year had the highest quantity sold?
* Which region received the highest discount?
* How are sales distributed across different regions?
* Which products are being sold?
* How does sales performance change from year to year?
* How does quantity sold change over time?

Instead of manually checking large amounts of sales data, users can view the important information directly from the dashboard.

# Problem Statement

A company may have sales transactions for different:

* Products
* Years
* Months
* Regions
* Quantities
* Sales amounts
* Discounts

Analyzing this information manually can be time-consuming.

Management needs a simple way to understand:

* Sales performance
* Product demand
* Regional performance
* Yearly growth
* Discount distribution

This dashboard solves the problem by presenting the data through **KPIs, charts, filters, and visual comparisons**.

#  Project Objectives

The main objectives of this project are:

1. Analyze total sales.
2. Analyze total quantity sold.
3. Analyze total sales amount.
4. Analyze total discounts.
5. Compare sales across regions.
6. Analyze monthly/yearly quantity sold.
7. Compare yearly sales.
8. Analyze discounts by region.
9. Identify high-performing regions.
10. Identify sales trends.
11. Provide interactive filters for detailed analysis.
12. Support data-driven commercial decisions.

#  Data Used

The dashboard is based on commercial/sales transaction data.

Important fields used for analysis include:

* Item
* Year
* Month
* Region
* Quantity
* Sales
* Amount
* Discount

The products shown in the dashboard include:

* Computer
* iPad
* Laptop
* MacBook

#  Data Preparation

Before creating the dashboard, the sales data was prepared and checked.

## 1. Checking Duplicate Records

Duplicate records were checked to make sure the same transaction was not counted multiple times.

**Purpose:**
To improve the accuracy of sales and quantity calculations.

## 2. Checking Missing Values

The dataset was checked for missing or blank values in important columns such as:

* Item
* Region
* Year
* Month
* Quantity
* Sales
* Amount
* Discount

Missing or incorrect values were handled before creating the dashboard.

## 3. Checking Data Types

The columns were checked to make sure they had the correct data type.

For example:

| Column   | Data Type |
| -------- | --------- |
| Item     | Text      |
| Region   | Text      |
| Year     | Number    |
| Month    | Text/Date |
| Quantity | Number    |
| Sales    | Number    |
| Amount   | Number    |
| Discount | Number    |

Correct data types are important for accurate calculations and charts.

#  Tools Used

The dashboard can be documented based on the visible features as an **Excel-based dashboard**.

### Technologies / Tools

* **Microsoft Excel**
* **PivotTables**
* **PivotCharts**
* **Slicers**
* **Excel formulas/calculations**
* **Data Cleaning**
* **Data Visualization**

The dashboard uses interactive filters for **Item, Year, and Month**.

#  KEY PERFORMANCE INDICATORS

The top section of the dashboard contains four important KPIs.

##  Total Sales

**Total Sales = 89,981,995.5**

This represents the total sales generated from the available data.

### Purpose

It provides a quick overview of the company's overall sales performance.

##  Total Quantity

**Total Quantity = 98,875**

This represents the total number of products/units sold.

### Purpose

It helps understand the overall sales volume and product demand.

##  Total Amount

**Total Amount = 94,717,890**

This represents the total amount associated with the sales transactions.

### Purpose

It helps management understand the overall transaction value.

##  Total Discount

**Total Discount = 4,735,894.5**

This represents the total discount provided on the sales.

### Purpose

It helps management understand how much discount was given to customers and evaluate the effect of discounts on commercial performance.

#  DASHBOARD VISUALIZATIONS

## 1. Monthly / Yearly Quantity Sold

The dashboard contains a horizontal bar chart showing quantity sold across different years.

The displayed years include:

* 2019
* 2020
* 2021

### Purpose

This chart helps understand changes in sales volume over the years.

It can answer:

> Which year had the highest quantity sold?

From the displayed dashboard, **2020 has the highest quantity sold** among the shown years.

### Business Usage

Management can use this information to:

* Plan inventory.
* Set sales targets.
* Understand product demand.
* Compare yearly sales volume.

#  2. Region Sales

A pie chart shows the distribution of sales across different regions.

The regions shown are:

* East
* West
* North
* South

The displayed distribution is approximately:

* **South – 43%**
* **East – 23%**
* **North – 23%**
* **West – 11%**

### Purpose

This chart helps identify which regions contribute more to total sales.

### Business Usage

It can help management:

* Identify strong markets.
* Identify weaker regions.
* Plan regional marketing.
* Allocate resources.
* Set regional sales targets.

The dashboard shows that **South has the largest share of regional sales**.

#  3. Discounts Through Region

A line chart is used to compare discount-related values across regions.

The regions include:

* East
* North
* South
* West

The chart compares:

* Sum of Discount
* Sum of Total Amount

### Purpose

This helps management understand how discounts vary across different regions.

### Business Usage

Management can use this analysis to determine:

* Which region receives more discounts.
* Whether discounts are concentrated in specific regions.
* How discount strategies differ between markets.
* Whether discounting needs to be controlled or increased.

#  4. Yearly Sales

A yearly sales chart compares sales for:

* 2019
* 2020
* 2021

The displayed values are approximately:

* 2019 → 73,202
* 2020 → 73,932
* 2021 → 73,765

### Purpose

This chart helps identify yearly sales performance.

It allows management to compare sales between years and identify changes in business performance.

### Business Usage

Yearly sales analysis can help with:

* Sales forecasting.
* Annual target setting.
* Business planning.
* Performance evaluation.
* Identifying growth patterns.

#  5. Item Filter

The dashboard provides an **Item slicer**.

The available items include:

* Computer
* iPad
* Laptop
* MacBook

### Purpose

Users can select a particular product and analyze its performance.

For example:

> Selecting **Laptop** allows the user to focus the dashboard on laptop-related sales.

#  6. Year Filter

A **Year slicer** allows users to select:

* 2019
* 2020
* 2021

### Purpose

Users can analyze the dashboard for a specific year.

For example:

> Selecting 2020 shows the sales information related to 2020.

#  7. Month Filter

A **Month slicer** allows users to select individual months.

The dashboard contains:

* January
* February
* March
* April
* May
* June
* July
* August
* September
* October
* November
* December

### Purpose

This allows users to perform month-level analysis.

For example:

> A user can select **January** to analyze the sales performance for January.

#  How the Project Was Created

The project can be explained using the following workflow:

```text
Raw Sales Data
      ↓
Data Cleaning
      ↓
Data Preparation
      ↓
Create Calculations
      ↓
Create PivotTables
      ↓
Create PivotCharts
      ↓
Add Slicers
      ↓
Create Dashboard Layout
      ↓
Analyze Sales Performance
      ↓
Generate Business Insights
```

#  Step 1 – Data Cleaning

The raw sales dataset was first checked for:

* Duplicate records
* Missing values
* Incorrect values
* Incorrect data types
* Formatting issues
* Inconsistent product names
* Inconsistent region names

The data was cleaned before performing the analysis.

#  Step 2 – Data Analysis

After cleaning the data, important business metrics were calculated.

These included:

* Total Sales
* Total Quantity
* Total Amount
* Total Discount
* Regional Sales
* Yearly Sales
* Quantity by Year
* Discount by Region

#  Step 3 – PivotTables

PivotTables were used to summarize the raw sales data.

For example, PivotTables can be used to calculate:

### Sales by Region

```text
Region → Sum of Sales

### Quantity by Year

```text
Year → Sum of Quantity

### Sales by Year

```text
Year → Sum of Sales

### Discount by Region

```text
Region → Sum of Discount

PivotTables make it easier to summarize large amounts of sales data.

#  Step 4 – PivotCharts

Charts were created from the summarized data.

The dashboard uses:

* Bar Chart
* Pie Chart
* Line Chart
* Column/3D Chart
* KPI Cards

Each chart was selected according to the type of information being displayed.

#  Step 5 – Add Slicers

Interactive slicers were added for:

* Item
* Year
* Month

Slicers allow users to filter the dashboard without changing the original dataset.

#  Step 6 – Dashboard Design

The dashboard was designed by arranging:

* KPI cards
* Charts
* Slicers
* Titles
* Labels
* Tables/visual elements

The objective was to create a dashboard that is:

* Simple
* Interactive
* Easy to read
* Visually organized
* Useful for business analysis

#  Key Business Insights

Based on the displayed dashboard, some important observations are:

* Total sales are approximately **89.98M**.
* Total quantity sold is approximately **98.88K**.
* Total amount is approximately **94.72M**.
* Total discount is approximately **4.74M**.
* The **South region** contributes the largest share of sales at approximately **43%**.
* **2020** has the highest displayed quantity sold.
* Sales can be compared across 2019, 2020, and 2021.
* Discounts vary across different regions.
* Product-level analysis can be performed using the Item slicer.
* Month and year filters allow more detailed sales analysis.

> The displayed values can change when Item, Year, or Month filters are applied.

#  Business Usage of the Dashboard

## 1. Sales Performance Monitoring

Sales managers can monitor overall sales and identify changes in sales performance.

## 2. Regional Performance Analysis

Management can compare different regions and identify the strongest and weakest markets.

## 3. Product Performance

The Item filter allows users to analyze products such as:

* Computer
* iPad
* Laptop
* MacBook

This helps identify which products are contributing to sales.

## 4. Inventory Planning

Quantity analysis can help the business understand product demand and plan inventory accordingly.

## 5. Discount Management

The discount analysis helps management understand where discounts are being given and how discount strategies vary by region.

## 6. Yearly Performance

Yearly sales analysis helps management compare business performance across different years.

## 7. Monthly Analysis

Month-level filtering can help identify seasonal changes and periods of higher or lower sales.

## 8. Sales Target Planning

Historical sales information can be used to set future sales targets.

## 9. Marketing Decisions

Regional and product-level sales information can help marketing teams decide where to focus promotions and campaigns.

## 10. Management Reporting

The dashboard provides a single visual report that can be used during business reviews and management meetings.

#  Benefits of the Project

This dashboard provides the following benefits:

* Converts raw sales data into useful information.
* Reduces manual reporting.
* Provides quick access to important KPIs.
* Makes sales trends easier to understand.
* Helps compare regional performance.
* Helps compare products.
* Helps monitor discounts.
* Supports inventory planning.
* Supports sales planning.
* Provides interactive filtering.
* Helps management make data-driven decisions.

#  Future Improvements

The dashboard can be improved further by adding:

* Profit analysis.
* Profit margin analysis.
* Product-wise sales ranking.
* Top 10 products.
* Bottom 10 products.
* Monthly sales trend.
* Year-over-year growth percentage.
* Regional profit analysis.
* Sales forecasting.
* Target vs actual sales.
* Product profitability.
* Interactive maps.
* Customer analysis.
* More advanced Excel automation.

# Skills Demonstrated

This project demonstrates practical skills in:

* Microsoft Excel
* Data Cleaning
* Data Analysis
* PivotTables
* PivotCharts
* Slicers
* Dashboard Development
* Data Visualization
* Sales Analysis
* Regional Analysis
* Product Analysis
* KPI Analysis
* Business Reporting
* Business Intelligence
* Data-driven Decision Making

#  Conclusion

The **Commercial Performance Dashboard** transforms raw sales data into an interactive Excel dashboard that provides a clear view of the company's commercial performance.

It combines **sales KPIs, quantity analysis, regional sales, yearly sales, discount analysis, and product/year/month filters** in one place.

The dashboard can help sales managers and management teams quickly understand business performance, identify strong regions and products, monitor discounts, plan inventory, and make **data-driven commercial decisions**.
