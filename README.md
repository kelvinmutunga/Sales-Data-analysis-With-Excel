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
  ![feature](https://github.com/user-attachments/assets/b4dc18a6-d604-48ef-b321-8fbee4e85ccf)

## Exploratory Data Analysis

### Sales Overview

- **Total Sales by Category:** Bar chart comparison of total quantity and sales by category

  
![image](https://github.com/user-attachments/assets/7e1fbdfe-2350-435f-b6ea-704c3e52dbff)
![image](https://github.com/user-attachments/assets/9e411256-7c2c-4ca3-afcb-fda60c65094d)
- **Total Sales by Business:** Highlighted top-performing businesses.

  
![image](https://github.com/user-attachments/assets/1412160b-bff3-4bc0-ab48-8d4a6d17530e)
![image](https://github.com/user-attachments/assets/094bdc11-c41d-4bdb-9e3d-1345da28021e)


### Trends Over Time
- Monthly sales trends identified peaks in **April and September**, with a decline in **December 2024**.
  
 ![image](https://github.com/user-attachments/assets/df111f93-cc9c-47dd-a183-ae65ab9a909a)

- **Product Sales Breakdown:**
  
![image](https://github.com/user-attachments/assets/19910d51-fc5d-45de-b149-d21a38b5a7ef)
![image](https://github.com/user-attachments/assets/dea73394-907c-4993-8995-9e6371def123)


![image](https://github.com/user-attachments/assets/d8d73773-81d3-4037-a07a-73b2abf089a4)
![image](https://github.com/user-attachments/assets/8bf69903-998c-4c8c-9274-5c753b4354bb)

### Performance Analysis
**Top Products by Quantity and Sales Value:**
- **Product-e805** leads in both categories.
- **Product-8f75** has high sales value but lower quantity.
- **Product-66e0** has consistent demand.

  
![image](https://github.com/user-attachments/assets/1f6d72dc-68ad-4940-b48a-9ccf13ededad)
![image](https://github.com/user-attachments/assets/fda3b2af-891a-4a75-86b3-a019d907cc03)
![image](https://github.com/user-attachments/assets/240973d9-d4c9-441a-8484-cf20cc80f66e)

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

  
![image](https://github.com/user-attachments/assets/b2401153-14f7-4835-9a03-55133c2f959e)

**Strategic Recommendations:**
- Align **sales strategies** to forecasts.
- Implement **promotions** in traditionally low-sales months.

### Anomaly Detection
- **December 2024:** Sharp decline in sales (-33.97%).
- **May & October 2024:** Significant sales spikes, likely due to seasonal trends.

  
![image](https://github.com/user-attachments/assets/2fb663da-45b6-4f68-9cf7-69ed3f5f9294)

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


![image](https://github.com/user-attachments/assets/a218d800-ae3a-4bc7-8bce-472fe518c1cc)

### Key Features of the Dashboard
- **Sales Overview** with interactive charts.
- **Customer Segmentation** for targeted strategies.
- **Performance Metrics** including total sales, quantity sold, and growth trends.

### Scalability
- **Real-time data updates** for dynamic decision-making.
- **Integration with business intelligence tools** for advanced reporting.

---
**GitHub Repository:** (https://github.com/kelvinmutunga/Sales-Data-analysis-With-Excel/)  
_Last Updated: January 2025_
