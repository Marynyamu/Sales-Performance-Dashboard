# 📊 Sales Performance & Financial Analysis Dashboard | Power BI

## Project Overview

This project is an interactive **Sales Performance and Financial Analysis Dashboard** developed using **Microsoft Power BI**.

The purpose of the project was to transform financial and sales data into an interactive business intelligence dashboard that allows management to monitor revenue, profitability, costs, sales volume, product performance, country performance, and financial trends.

The project combines my **finance background** with practical skills in **Power BI, DAX, data modeling, KPI development, and financial analysis**.

---

## 🎯 Business Problem

Management needs a simple and interactive way to monitor sales and financial performance across different countries, products, segments, and time periods.

The dashboard was developed to answer questions such as:

* What is the total revenue?
* How much profit is being generated?
* What is the total cost of goods sold?
* How many units have been sold?
* How many countries are represented in the sales data?
* How many products are being analyzed?
* Which countries generate the most sales?
* Which segments generate the most profit?
* How does sales performance change over time?
* How is revenue growth distributed across countries?

---

## 🎯 Project Objectives

The main objectives of the project were to:

1. Monitor overall sales and financial performance.
2. Track total revenue and gross sales.
3. Monitor total profit and cost of goods sold.
4. Analyze sales performance by country.
5. Analyze profitability by market segment.
6. Monitor units sold.
7. Analyze the number of countries and products in the dataset.
8. Analyze monthly sales and profit trends.
9. Analyze revenue growth across countries.
10. Provide management with an interactive financial reporting tool.

---

# 🗂️ Dataset

The project uses Microsoft's **Financial Sample** dataset.

The dataset contains financial and sales-related information including:

* Segment
* Country
* Product
* Discount Band
* Units Sold
* Manufacturing Price
* Sale Price
* Gross Sales
* Discounts
* Sales
* COGS
* Profit
* Date
* Month
* Year

### Data Source

Microsoft Power BI Financial Sample:

https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download

The dataset is a sample dataset provided for learning and demonstration purposes.

---

# 🛠️ Tools & Technologies

### Power BI Desktop

Used to build the interactive dashboard, financial KPIs, charts, slicers, and report pages.

### Power Query

Used for data preparation and transformation.

### DAX

Used to create financial measures and KPIs.

### Excel

Used as the original source format for the financial dataset.

---

# 📐 Data Model

A calendar table was created to support time-based analysis.

The model connects the calendar table to the financial data through the date field.

```text
Calendar[Date]
      │
      │
      ▼
Financials[Date]
```

This enables analysis by:

* Year
* Month
* Date
* Time period

---

# 📊 Key Performance Indicators

The dashboard includes the following KPIs:

### Total Revenue

```DAX
Total Revenue =
SUM(financials[Sales])
```

Measures the total sales revenue in the dataset.

### Total Profit

```DAX
Total Profit =
SUM(financials[Profit])
```

Measures the total recorded profit.

### Total Units Sold

```DAX
Total unit sold =
SUM(financials[Units Sold])
```

Measures the total number of units sold.

### Total COGS

```DAX
Total COGS =
SUM(financials[COGS])
```

Measures the total cost of goods sold.

### Total Gross Sales

```DAX
Total Gross Sales =
SUM(financials[Gross Sales])
```

Measures sales before discounts.

### Number of Countries

```DAX
Countries =
DISTINCTCOUNT(financials[Country])
```

Measures the number of unique countries represented in the dataset.

### Number of Products

```DAX
Products =
DISTINCTCOUNT(financials[Product])
```

Measures the number of unique products represented in the dataset.

---

# 📑 Dashboard Pages

## 1. Executive Financial Review

The **Executive Financial Review** provides a high-level overview of financial and sales performance.

### KPIs

The page includes:

* Total Revenue
* Total Profit
* Total Units Sold
* Total COGS
* Total Gross Sales

### Visual Analysis

The page includes:

* Profit and Sales by Month
* Sales by Country
* Profit by Segment
* Country filter
* Year filter
* Segment filter

### Business Purpose

This page is designed to provide management with a quick overview of the company's sales and financial performance.

### Screenshot

![Executive Financial Review](screenshots/executive-financial-review.png)

---

# 2. Sales Analysis

The **Sales Analysis** page provides a more detailed view of sales performance.

### KPIs

The page includes:

* Total Revenue
* Number of Countries
* Number of Products
* Total Sales
* Total Units Sold
* Total COGS

### Visual Analysis

The page includes:

* Revenue by Month
* Revenue Growth by Country
* Sales by Country
* Sales by Country comparison
* Product filter
* Year filter

### Business Purpose

This page allows users to investigate sales performance in greater detail and identify differences between countries, products, and time periods.

### Screenshot

![Sales Analysis](screenshots/sales-analysis.png)

---

# 📈 Financial & Sales Analysis

The dashboard allows users to analyze several important areas of business performance.

## Revenue Analysis

Revenue can be analyzed by:

* Country
* Product
* Month
* Year

This helps identify major revenue contributors and changes in sales performance over time.

## Profitability Analysis

Profitability can be analyzed using:

* Total Profit
* COGS
* Profit by Segment
* Monthly Profit

This provides insight into where the business is generating profit.

## Geographic Analysis

Country-level analysis allows management to compare sales and revenue growth across different markets.

## Product Analysis

The dashboard allows users to filter and analyze products based on their contribution to sales performance.

## Time-Based Analysis

Monthly analysis helps identify changes and trends in sales and profit over time.

---

# 🔍 Key Business Questions

The dashboard was designed around the following business questions:

### Revenue

* How much revenue is being generated?
* Which countries generate the highest sales?
* How does revenue change over time?

### Profitability

* How much profit is being generated?
* Which segments generate the highest profit?
* How does profit change over time?

### Sales Volume

* How many units have been sold?
* Which products and markets contribute to sales volume?

### Geographic Performance

* Which countries contribute the most sales?
* Which countries show stronger or weaker revenue growth?

### Cost Management

* What is the total cost of goods sold?
* How does COGS compare with revenue and profit?

---

# 💡 Business Value

The dashboard demonstrates how financial and sales data can be transformed into an interactive management reporting tool.

The analysis can support:

* Revenue monitoring
* Profitability analysis
* Sales performance monitoring
* Country-level performance analysis
* Product performance analysis
* Cost monitoring
* Trend analysis
* Management reporting

---

# 📚 Skills Demonstrated

This project demonstrates practical skills in:

* Financial analysis
* Sales analysis
* Power BI
* Power Query
* DAX
* Data transformation
* Data modeling
* KPI development
* Business intelligence
* Data visualization
* Time-based analysis
* Interactive dashboard design
* Management reporting
* Business insight generation

---

# ⚠️ Data Limitations

This project uses Microsoft's sample Financial dataset for educational and portfolio purposes.

It should not be interpreted as confidential company financial information.

The dataset is primarily focused on sales and profitability information. It does not represent a complete general ledger or a complete set of statutory financial statements.

Therefore, this dashboard should be considered a **sales performance and financial analysis project**, rather than a complete accounting or financial reporting system.

---

# 🚀 Future Improvements

Future versions of this project could include:

* Budget vs Actual analysis
* Forecast vs Actual analysis
* Cash flow analysis
* Accounts Receivable ageing
* Accounts Payable ageing
* Working capital analysis
* Expense analysis
* Customer profitability analysis
* Financial forecasting
* Automated financial reporting
* Power BI Service deployment
* Row-level security

---

# 👩‍💻 Author

## Mary Nyamu

**Finance Professional | Aspiring Financial/Data Analyst**

LinkedIn:

https://www.linkedin.com/in/mary-nyamu

---

## 📌 Project Purpose

This project demonstrates my ability to combine **finance knowledge, data analysis, and business intelligence** to transform financial data into an interactive dashboard that can support management decision-making.
