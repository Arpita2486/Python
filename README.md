#  Instacart Grocery Basket Analysis

**Role:** Data Analyst – Exploratory Data Analysis & Customer Segmentation  
**Tools Used:** Python, Pandas, NumPy, Seaborn, Matplotlib, Jupyter Notebook, Anaconda  

##  Project Summary

In this project, I worked as a data analyst for **Instacart**, an online grocery store, to uncover insights from sales data and customer behavior. The business goal was to understand purchasing trends, identify customer segments, and provide actionable strategies for marketing and sales targeting.

This was a **full-cycle analysis project**, beginning with data wrangling and ending in stakeholder reporting. The analysis helped identify **busiest shopping times**, **loyalty patterns**, **price sensitivities**, and **product preferences** across customer profiles.

##  Key Business Questions Answered

- What are the busiest days and hours for orders?
- At what time of day do customers spend the most money?
- Which price ranges drive purchasing behavior?
- What product types and departments are most frequently ordered?
- How do customer demographics (age, income, family status, region) affect order behavior?
- What are the differences between high-loyalty and low-loyalty customers?

##  Technical Contributions

- **Data Import & Cleaning**
  - Merged multiple datasets from Instacart and custom customer profiles using `pandas.merge()`
  - Cleaned missing, duplicate, and inconsistent data entries
  - Standardized data types and column naming conventions

- **Data Engineering**
  - Created new variables using `if` statements, `loc[]`, and functions for flags like:
    - Loyalty (`loyalty_flag`)
    - Spending category (`spending_flag`)
    - Order frequency (`order_frequency_flag`)
  - Performed consistency checks and filtered noisy data

- **Data Aggregation**
  - Grouped data using `groupby()` to analyze:
    - Total and average spend per user
    - Average basket size
    - Repeat ordering patterns
    - Brand loyalty distribution

- **Data Visualization**
  - Generated charts using `matplotlib` and `seaborn`:
    - Bar plots, line charts, histograms, and scatter plots
    - Visual analysis of time-of-day trends, department order frequencies, and customer segments

- **Reporting**
  - Created summary tables and visual dashboards
  - Delivered final analysis and marketing recommendations in an Excel report
  - Followed ethical data practices with anonymized customer data
