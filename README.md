## TeleConnect Customer Churn Analysis

### Project Overview
This project analyzes customer churn for TeleConnect, a telecommunications company. The goal was to identify key drivers of customer churn and provide data-driven retention recommendations.

### Business Problem
TeleConnect is facing customer retention challenges. This analysis seeks to answer:
- Which customer demographics are most likely to churn?
- What services, contracts, and payment methods drive loyalty?

### Methodology
This project followed the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) framework:
1.  **Business Understanding** - Defined objectives to reduce churn.
2.  **Data Understanding** - Explored a dataset of 7,043 customers.
3.  **Data Preparation** - Cleaned data and created a `churn_flag`.
4.  **Analysis (Modeling)** - Performed exploratory data analysis to find patterns.
5.  **Evaluation** - Interpreted findings to identify key drivers like internet service and contract type.
6.  **Recommendations** - Delivered actionable strategies for the business.

### Key Findings
- **Key Driver:** Customers with **month-to-month contracts** and **no internet service** have the highest churn risk.
- Those who pay with electronic checks, especially those with low monthly charges have the highest churn, at 42.8%.
- Highest monthly charges correlate with lower churn across all payment methods, iondicating that most high spending clients are loyal.

### Recommendations
- Target month-to-month contract customers customers without internet access with special internet access offers (free installation, first month discounts, etc).
- Target one-year contract customers with phone service bundles, online backup and streaming TV.
- Convert customers who pay with electronic checks to other automatic payment methods. Target those with lowest monthly charges first as they are the highest risk.
- Design loyalty programs that reward increased spending (i.e. discounts on additional services).
- Impliment win-back campaigns for churned customers. Create incentives that make it easier to hop back onto the service.
- Train customer service agents to spot high risk clients and proactively offer retention packages.

### Repository Structure
- Python notebook.
- Original dataset (csv file).
