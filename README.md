# Shield Insurance Dashboard Project

This project was created as part of my virtual internship at AtliQ Technologies.

**[Live Dashboard Link](https://app.powerbi.com/groups/me/reports/62be3270-b161-48b8-a46c-d9e49427e074?pbi_source=desktop)**

## Project Overview

Shield Insurance, a major insurance provider in India, operates across five cities: Mumbai, Delhi NCR, Chennai, Hyderabad, and Indore. The company offers nine types of policies, selling through both offline and online channels.

The aim of this project was to analyze Shield Insurance’s operational data, gathered between November 2022 and April 2023, to drive data-informed business decisions. The data was visualized in an interactive Power BI dashboard, highlighting key metrics like revenue trends, customer acquisition, and policy performance.

## Data Model

The analysis was performed using a star schema consisting of:

- **3 Dimension Tables**: `Dim_customer`, `Dim_date`, `Dim_policies`
- **2 Fact Tables**: `Fact_premiums`, `Fact_settlements`

This schema allowed efficient exploration of customer behavior, policy uptake, and settlement details.

![Shield Insurance Data Model](https://github.com/Shimrangupta22/Shield-Insurance/blob/main/assets/data%20modeling.png)

## Dashboard Highlights

### **Home Page**
The home page serves as the main navigation hub, allowing users to easily explore various sections of the dashboard and access key insights at a glance.

![Home Page](https://github.com/Shimrangupta22/Shield-Insurance/blob/main/assets/landing%20page.png)

### **General Overview**
This section provides a comprehensive summary of essential business metrics such as revenue trends, customer demographics, and policy performance, with breakdowns by age group and city.

![General Overview](https://github.com/Shimrangupta22/Shield-Insurance/blob/main/assets/general%20analysis.png)

### **Sales Channel Performance**
Here, users can track revenue performance across different sales channels, illustrating the revenue contribution of both offline and online channels. Offline agents currently dominate sales, while online channels show potential for growth.

![Sales Channel Analysis](https://github.com/Shimrangupta22/Shield-Insurance/blob/main/assets/sales%20mode%20analysis.png)

### **Age Group Performance**
This section delves into customer acquisition and revenue contribution by different age groups, highlighting settlement trends and policy preferences across age demographics.

![Age Group Performance](https://github.com/Shimrangupta22/Shield-Insurance/blob/main/assets/age%20group%20analysis.png)

## Key Insights

### Overall Performance:
- **Total Revenue**: ₹989.3M, up by 18.40% from the previous month.
- **Total Customers**: 27K, marking an 18.28% increase over the last month.
- **Revenue Trend**: March 2023 recorded the highest revenue of ₹263.8M, followed by December 2022 (₹153.7M) and April 2023 (₹142.6M).

### City-Wise Performance:
- **Delhi NCR**: The top-performing region with ₹401.57M in revenue and 11,007 customers.
- **Mumbai**: Generated ₹239.51M from 6,432 customers.
- **Hyderabad**: Brought in ₹160.52M from 4,340 customers.
- **Chennai**: Recorded ₹106.31M in revenue from 2,966 customers.
- **Indore**: Contributed ₹81.35M from 2,096 customers.

### Sales Channels:
- **Offline agents** dominate sales, contributing ₹550.76M in revenue with 14.87K customers.
- **Online channels** (specifically the app) are growing rapidly, generating ₹160.97M.

### Demographic Insights:
- The **31-40 age group** is the highest contributor to revenue, generating ₹335.72M from 10,977 customers.
- The **65+ age group** shows higher settlement costs, indicating increased risk.

### Policy Preferences:
- **POL4321HEL** is the most popular policy among the 31-40 age group.
- **POL2005HEL** is a favorite in the 65+ age group due to the higher settlement needs.

## Recommendations

1. **Enhance Digital Sales Channels**: Invest more in improving the app and website to attract and convert more online customers.
2. **Target the 31-40 Age Group**: Develop tailored products and offers to maximize revenue from this highly profitable segment.
3. **Expand Policies for the 65+ Segment**: Focus on creating specialized policies to address the higher settlement demands of this age group.
4. **Boost Regional Marketing in Delhi NCR and Mumbai**: With these cities generating the highest revenue, regional campaigns should focus on further customer acquisition.
5. **Incentivize Offline Agents**: Continue supporting offline sales by incentivizing agents, encouraging cross-selling and up-selling of policies.

## Conclusion

The Shield Insurance dashboard provides a detailed analysis of the company's performance across key metrics such as customer acquisition, revenue growth, and policy effectiveness. These insights will help Shield Insurance make data-driven decisions to optimize its business strategies and future growth.
