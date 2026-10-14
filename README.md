# Olist E-Commerce Sales & Customer Insights Dashboard

## Project Overview

This project presents an interactive Power BI dashboard developed to analyse e-commerce sales performance, order trends, customer distribution, product categories, seller performance, delivery efficiency, payment methods, and customer reviews using the Olist Brazilian E-Commerce dataset.

The dashboard transforms raw e-commerce data into actionable business insights through key performance indicators (KPIs), interactive visualisations, and dynamic slicers. It enables users to explore business performance across different years, customer states, and product categories.

## Business Objectives

The main objectives of this project are to:

- Evaluate overall sales and payment performance.
- Monitor order volumes and monthly sales trends.
- Identify top-performing product categories and sellers.
- Understand customer distribution across Brazilian states.
- Analyse payment methods and order status.
- Evaluate delivery efficiency and freight costs.
- Examine customer review score distributions.
- Support data-driven decision-making through interactive reporting.

## Tools and Technologies

|Tool                               |Purpose                                                |
|-----------------------------------|-------------------------------------------------------|
|Power BI Desktop                   |Dashboard development and data visualisation           |
|DAX                                |KPI calculations and analytical measures               |
|MySQL                              |Data storage and querying                              |
|Power Query                        |Data preparation and transformation, where applicable  |
|Olist E-Commerce Dataset           |Source data for the analysis                           |

## Dashboard Features

### 1. Key Performance Indicators

The dashboard includes nine KPI cards:

|KPI                                 |Description                                             |
|------------------------------------|--------------------------------------------------------|
|Total Sales                         |Total product sales, excluding freight                  |
|Total Orders                        |Number of distinct orders                               |
|Average Order Value                 |Average product sales per order                         |
|Total Payment Value                 |Total recorded customer payment value                   |
|Total Customers                     |Number of customer records                              |
|Total Products                      |Number of distinct products in the product catalogue    |
|Average Delivery Time               |Average delivery time in days for delivered orders      |
|Total Freight                       |Total freight charges                                   |
|Average Item Price                  |Average price per order item                            |

### 2. Sales Performance Analysis

The sales visuals explore:

- Monthly sales trends.
- Sales by product category.
- Sales performance across customer states.
- Top 10 sellers ranked by sales.

### 3. Order and Customer Analysis

The dashboard also includes:

- Monthly order volume.
- Order status distribution.
- Customer review score distribution.
- Payment method analysis.

## 4. Interactive Filtering

Users can dynamically filter the dashboard using:

- Year: Explore performance over time.
- Customer State: Compare results across Brazilian states.
- Product Category: Investigate the performance of individual product categories.

These slicers enable users to examine specific segments and compare business performance under different conditions.

## Key Metrics

The following values represent the initial project results before applying interactive filters:

|Metric                                      |Result              |
|--------------------------------------------|--------------------|
|Total Product Sales                         |13,591,643.70       |
|Total Orders                                |99,441              |
|Average Order Value                         |136.68              |
|Total Payment Value                         |16,008,872.12       |
|Customer Records                            |99,441              |
|Distinct Products                           |32,951              |
|Average Delivery Time                       |12.5 days           |
|Total Freight                               |2,251,909.54        |
|Average Item Price                          |120.65              |

Note: The currency symbol and number formatting displayed in the dashboard should be interpreted according to the project's documented currency convention. The $ symbol used in the visuals is a display choice and does not itself convert the source values into US dollars. Confirm and document the source currency before interpreting or comparing monetary results.

## Data Analysis Approach

The project follows a structured analytical workflow:

1. Data preparation: Load the Olist datasets and prepare the relevant tables for analysis.
2. Data modelling: Establish and validate relationships between customers, orders, order items, products, sellers, and payment data as required.
3. Measure development: Create DAX measures for sales, order counts, average order value, payment value, freight, item prices, and delivery time.
4. Visualisation: Develop KPI cards, line charts, bar charts, and donut charts to communicate the findings.
5. Interactivity: Add slicers and test their interactions with the dashboard visuals.
6. Validation: Check KPI values, sorting, chart readability, and filtering behaviour.
7. Reporting: Present the analysis in an interactive dashboard designed to support business decisions.

## Initial Business Insights

The initial results provide several opportunities for further investigation:

- Sales and payments: Product sales and total recorded payments differ. This warrants investigation into freight, payment records, order composition, and the definitions used for each measure.
- Delivery performance: The average delivery time of 12.5 days provides a baseline for evaluating logistics efficiency and identifying potential delays.
- Seller performance: The Top 10 Sellers chart allows high-performing sellers to be identified and compared.
- Product categories: Category-level sales analysis helps identify which product categories contribute most to revenue.
- Customer experience: Review score distributions provide a starting point for examining customer satisfaction and its relationship with delivery performance.
- Geographic performance: State-level analysis helps explore where sales are concentrated and where additional growth opportunities may exist.

## Repository Structure
```Text
Olist-Ecommerce-PowerBI-Analysis/
│
├── Olist_Ecommerce_Sales_Customer_Insights.pbix
├── README.md
│
├── screenshots/
│   └── dashboard_overview.png
│
└── sql/
    └── analysis_queries.sql
```

## How to Use the Project

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open Olist_Ecommerce_Sales_Customer_Insights.pbix.
4. If prompted, configure the data source connection and credentials for your own environment.
5. Refresh the data if the source files and database are available.
6. Explore the dashboard using the Year, Customer State, and Product Category slicers.

## Dataset

This project uses the Olist Brazilian E-Commerce dataset, which contains information about orders, customers, products, sellers, payments, shipping, and reviews.

Dataset information: Brazilian E-Commerce Public Dataset by Olist on Kaggle

Refer to the dataset provider's terms and licensing information before redistributing source data.

## Future Improvements

Potential enhancements include:

- Add year-over-year and month-over-month growth measures.
- Analyse late deliveries and estimated-versus-actual delivery dates.
- Investigate the relationship between review scores and delivery performance.
- Add customer segmentation and repeat-purchase analysis.
- Develop a dedicated executive summary page.
- Add drill-through pages for sellers and product categories.
- Publish an online version of the dashboard where appropriate.

## Skills Demonstrated

- Data analysis and interpretation
- Power BI dashboard development
- DAX measure creation
- Data modelling and validation
- KPI design and performance monitoring
- Interactive data visualisation
- Business intelligence reporting
- Communicating analytical findings

Author

Perseverance Mutengera

BSc Computing Graduate | Data Analytics | Power BI | SQL | Python

This project demonstrates my practical application of data analytics and business intelligence techniques to explore e-commerce performance and communicate findings through interactive reporting.

This project was developed for learning and portfolio demonstration purposes.
