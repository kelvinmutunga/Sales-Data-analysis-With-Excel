# Sales and Customer Data Analysis Report

## Table of Contents
1. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
   - [Executive Summary](#executive-summary)
   - [Data Quality Assessment](#data-quality-assessment)
   - [Feature Engineering](#feature-engineering)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
   - [Sales Overview](#sales-overview)
   - [Trends Over Time](#trends-over-time)
   - [Performance Analysis](#performance-analysis)
3. [Advanced Analysis](#advanced-analysis)
   - [Customer Segmentation](#customer-segmentation)
   - [Forecasting](#forecasting)
   - [Anomaly Detection](#anomaly-detection)
   - [Correlation Analysis](#correlation-analysis)
4. [Strategic Insights and Recommendations](#strategic-insights-and-recommendations)
   - [Product Strategy](#product-strategy)
   - [Customer Retention](#customer-retention)
   - [Operational Efficiency](#operational-efficiency)
   - [Sales Growth](#sales-growth)
5. [Dashboard and Reporting](#dashboard-and-reporting)
   - [Key Features of the Dashboard](#key-features-of-the-dashboard)
   - [Scalability](#scalability)
![kwanza](https://github.com/user-attachments/assets/28f470ae-c219-44ed-bb0d-584413d70491)

## Data Cleaning and Preparation
![feature](https://github.com/user-attachments/assets/b4dc18a6-d604-48ef-b321-8fbee4e85ccf)

### Executive Summary
This report analyzes sales and customer data, focusing on identifying key trends, anomalies, customer segmentation, and strategic insights. Key performance indicators (KPIs) include:
- Total sales value
- Total quantity sold
- Sales growth rate
- Correlation between quantity and sales value

### Data Quality Assessment
**Issues Identified:**
- **Missing Values:** Imputed using the median value for each respective product.
- **Duplicates:** Removed to maintain dataset integrity.
- **Inconsistent Data Types:** Reformatted date columns to datetime format.

### Feature Engineering
- Created a new column `Month-Year` for trend analysis using:
  ```excel
  =TEXT(DATE, "mmm-yyyy")
  ```

## Exploratory Data Analysis

### Sales Overview
- **Total Sales by Category:** Bar chart comparison of total quantity and sales by category.
- **Total Sales by Business:** Highlighted top-performing businesses.

### Trends Over Time
- Monthly sales trends identified peaks in **April and September**, with a decline in **December 2024**.
- **Product Sales Breakdown:**
  ```
  | Product   | Total Sales (KES) | Percentage |
  |-----------|------------------|------------|
  | Product-29ee | 68,248,274 | 11.05% |
  | Product-4156 | 56,956,007 | 9.22% |
  | Product-66e0 | 70,704,225 | 11.45% |
  | Product-8f75 | 158,797,460 | 25.72% |
  | Product-e805 | 262,787,281 | 42.56% |
  ```

### Performance Analysis
**Top Products by Quantity and Sales Value:**
- **Product-e805** leads in both categories.
- **Product-8f75** has high sales value but lower quantity.
- **Product-66e0** has consistent demand.

**Strategic Recommendations:**
- **Amplify marketing** for **Product-e805**.
- **Evaluate pricing strategies** for **Product-8f75**.
- **Monitor inventory** for **Product-66e0**.

## Advanced Analysis

### Customer Segmentation
**Segmenting by:**
1. **Total Quantity Purchased**
2. **Transaction Frequency**
3. **Total Sales Value**

**Findings:**
- **Balanced Distribution** across High, Medium, and Low categories.
- **High-Frequency Customers** should be targeted with loyalty programs.
- **Low-Frequency Customers** need re-engagement campaigns.

### Forecasting
**Sales Forecast for Jan-Mar 2025 (KES):**
- **January:** 124,198,336
- **February:** 124,255,308
- **March:** 124,312,280

**Strategic Recommendations:**
- Align **sales strategies** to forecasts.
- Implement **promotions** in traditionally low-sales months.

### Anomaly Detection
- **December 2024:** Sharp decline in sales (-33.97%).
- **May & October 2024:** Significant sales spikes, likely due to seasonal trends.

### Correlation Analysis
- **Quantity vs Sales Value Correlation:** 0.835 (Strong Positive Relationship)
- **Strategy:** Focus on **increasing quantity** to drive total sales.

## Strategic Insights and Recommendations

### Product Strategy
- **Prioritize Product-e805** for marketing and inventory management.
- **Diversify product portfolio** to avoid over-reliance on top products.

### Customer Retention
- **VIP programs** for high-value customers.
- **Referral incentives** for medium-value customers.
- **Discounts & promotions** for low-value customers.

### Operational Efficiency
- **Monitor stock levels** for consistently high-demand products.
- **Optimize supply chain** to reduce delays and improve responsiveness.

### Sales Growth
- **Seasonal promotions** to mitigate downturns in slow months.
- **Bundle offers** to increase purchase frequency and volume.

## Dashboard and Reporting

### Key Features of the Dashboard
- **Sales Overview** with interactive charts.
- **Customer Segmentation** for targeted strategies.
- **Performance Metrics** including total sales, quantity sold, and growth trends.

### Scalability
- **Real-time data updates** for dynamic decision-making.
- **Integration with business intelligence tools** for advanced reporting.

---
**GitHub Repository:** [YourRepoLinkHere](#)  
_Last Updated: January 2025_
