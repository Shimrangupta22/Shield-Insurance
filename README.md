# Shield Insurance Dashboard Project

This project was completed as part of my virtual internship at AtliQ Technologies.

**[Live Dashboard Link](https://app.powerbi.com/groups/me/reports/62be3270-b161-48b8-a46c-d9e49427e074?pbi_source=desktop)**

## Project Overview

Shield Insurance is a leading provider operating in five major Indian cities: Mumbai, Delhi NCR, Chennai, Hyderabad, and Indore. The company leverages multiple channels such as Offline Agents, Direct Sales, Mobile App, and Website to offer a range of nine insurance policies.

The objective of this project was to provide a detailed analysis of the company's data, spanning from November 2022 to April 2023, to support data-driven decision-making.

## Data Model

For this project, I used a Star Schema consisting of:

- **3 Dimension Tables**: `Dim_customer`, `Dim_date`, and `Dim_policies`
- **2 Fact Tables**: `Fact_premiums` and `Fact_settlements`

The model was designed to streamline the analysis of customer demographics, policies, premiums, and settlements.

![Shield Insurance Data Model](https://github.com/Shimrangupta22/Shield-Insurance/blob/main/assets/data%20modeling.png)

## Dashboard Features

### **Home Page**
This is the default landing page for users, providing easy navigation to other sections of the dashboard.

![Home Page](https://github.com/user-attachments/assets/4c86e911-c87f-41b4-aea9-d9e95c662d8f)

### **General Overview**
The general analysis section highlights key metrics such as revenue trends, customer demographics, and policy performance. It includes breakdowns by age group and city.

![General Overview](https://github.com/user-attachments/assets/e7ed8330-e2f8-4b7d-83df-12d88e0edb2e)

### **Sales Channel Analysis**
This section focuses on revenue generation across different sales modes, showcasing which channels contributed the most revenue over time.

![Sales Channel Analysis](https://github.com/user-attachments/assets/04575041-dfaa-4a66-961b-696c240cb9fb)

### **Age Group Performance**
Here, we analyze revenue and customer acquisition across various age groups, including settlement estimates and policy preferences.

![Age Group Performance](https://github.com/user-attachments/assets/68b72b1a-440b-48a0-840c-68b8b83a4bc6)

## Insights & Recommendations

### Age Group Performance:
- **Highest Revenue**: The 31-40 age group generates the most revenue.
  
  **Actionable Insights**:
  - Focus marketing campaigns on this group.
  - Develop strategies to attract the 41-50 and 65+ age demographics.

### Sales Mode Analysis:
- **Top Performer**: Offline agents drive the highest revenue, but online platforms (app and website) have seen growth post-February 2023.
  
  **Recommendations**:
  - Enhance features on the online platforms.
  - Provide personalized policy suggestions based on customer input to boost online sales.

### City Performance:
- **Key Markets**: Delhi NCR, Mumbai, and Hyderabad are leading in both revenue and customer base.
  
  **Recommendations**:
  - Replicate successful strategies in these cities across other regions to maximize reach.

### Policy Analysis:
- **Top Policy**: POL2005HEL has the highest revenue contribution.
  
  **Recommendations**:
  - Develop variations of the POL2005HEL policy to attract more customers.
  - Offer additional policy riders to increase customization options.

## Conclusion

This project provides Shield Insurance with actionable insights into their sales channels, customer demographics, and policy performance. The Power BI dashboard serves as a comprehensive tool for monitoring business performance and driving strategic decisions.

