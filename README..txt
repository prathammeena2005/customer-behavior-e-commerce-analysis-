# Customer Behavior & E-Commerce Analytics

A Python-based data analytics project that analyzes customer purchasing behavior, membership performance, discounts, satisfaction, customer segmentation, and business patterns.

## Project Overview

This project was developed as part of the AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 | BharatCares.

The project analyzes a customer dataset containing 350 customer records and 12 columns to identify meaningful behavioral patterns and generate business insights using Python.

The analysis focuses on:
- Customer purchasing behavior
- Customer spending patterns
- Membership performance
- Discount analysis
- Customer satisfaction
- Customer segmentation
- Correlation analysis
- Data quality and outlier checks
- Business insights and recommendations

## Dataset

The project uses a customer behavior dataset containing information such as:
- Customer ID
- Age
- Gender
- City
- Membership Level
- Total Spend
- Items Purchased
- Average Rating
- Discount Applied
- Days Since Last Purchase
- Satisfaction Level

Dataset Source: Kaggle

IMPORTANT: Add the exact Kaggle dataset URL here before final submission.

## Objectives

1. Understand customer purchasing behavior.
2. Analyze spending patterns across customer groups.
3. Compare Gold, Silver, and Bronze membership levels.
4. Analyze the relationship between discounts and customer behavior.
5. Study customer satisfaction and its relationship with spending and activity.
6. Segment customers based on value and activity.
7. Identify important relationships between numerical variables.
8. Perform data quality and outlier checks.
9. Generate actionable business insights and recommendations.

## Technologies Used

- Python
- Pandas - data manipulation and analysis
- NumPy - numerical operations
- Matplotlib - data visualization
- Seaborn - statistical visualization
- Google Colab / Jupyter Notebook - development environment

## Project Workflow

Dataset
  ↓
Data Loading
  ↓
Data Understanding
  ↓
Data Cleaning
  ↓
Exploratory Data Analysis
  ↓
Membership Analysis
  ↓
Discount Analysis
  ↓
Satisfaction Analysis
  ↓
Customer Segmentation
  ↓
Correlation Analysis
  ↓
Data Quality & Outlier Analysis
  ↓
Business Insights
  ↓
Recommendations

## Analysis Performed

### 1. Exploratory Data Analysis

The dataset was examined to understand its structure, data types, distributions, and customer characteristics.

### 2. Membership Analysis

Customer behavior was compared across:
- Gold
- Silver
- Bronze

Gold customers showed the highest average spending among the membership groups.

### 3. Discount Analysis

Customers with and without discounts were compared using:
- Total Spend
- Items Purchased
- Average Rating
- Days Since Last Purchase

The analysis is treated as descriptive because discount availability is structurally related to city in this dataset.

### 4. Satisfaction Analysis

Customer satisfaction was analyzed against:
- Spending
- Items Purchased
- Rating
- Recency
- Membership
- City
- Gender

Satisfied customers showed substantially higher average spending, purchase volume, and ratings than the other satisfaction groups.

### 5. Customer Segmentation

Customers were grouped into behavioral segments:
- High Value Active
- Potential High Value
- Moderate Value
- Low Value / Less Active

The largest segment was Moderate Value, containing 116 customers.

### 6. Correlation Analysis

Important relationships identified:

Items Purchased vs Total Spend: 0.972
Average Rating vs Total Spend: 0.941
Days Since Last Purchase vs Total Spend: -0.540
Age vs Total Spend: -0.678

These values represent associations in the dataset and should not be interpreted as proof of causation.

## Key Findings

- 350 customers were analyzed.
- Total customer spending was $295,883.60.
- Average customer spending was $845.38.
- San Francisco had the highest total customer spending in the dataset.
- Gold membership had the highest average spending among membership groups.
- Moderate Value was the largest customer segment with 116 customers.
- Items Purchased had a very strong positive association with Total Spend (0.972).
- Average Rating had a strong positive association with Total Spend (0.941).
- Days Since Last Purchase had a negative association with Total Spend (-0.540).
- Data quality checks found 2 missing Satisfaction Level values, with no duplicate rows or duplicate Customer IDs.

## Data Quality Checks

The project included checks for:
- Missing values
- Duplicate rows
- Duplicate Customer IDs
- Invalid age values
- Negative spending
- Negative item counts
- Invalid ratings
- Negative recency values
- IQR-based outliers

The dataset contained 2 missing Satisfaction Level records. No duplicate rows or duplicate Customer IDs were identified.

## Business Recommendations

1. Monitor high-value active customers and maintain engagement through relevant retention strategies.
2. Investigate less-active customers using recency and spending behavior to identify potential re-engagement opportunities.
3. Examine the relationship between membership benefits and customer spending/satisfaction using additional real-world data.
4. Evaluate discount strategies while controlling for city and membership.
5. Collect additional transaction-level and time-based data for stronger behavioral and causal analysis.

## Important Interpretation Note

The dataset contains highly structured relationships between variables such as City, Discount, Membership, and Satisfaction. Therefore, the findings should primarily be interpreted as descriptive associations, not causal effects.

Additional real-world transaction-level and time-based data would be useful for stronger business and causal analysis.

## Project Files

customer-behavior-ecommerce-analytics/
|
|-- PrathamMeena_CustomerBehavior_EcommerceAnalytics.ipynb
|-- requirements.txt
|-- PrathamMeena_CustomerBehavior_EcommerceAnalytics_ProjectReport.docx
|-- README.md

## How to Run the Project

### Option 1: Google Colab

1. Open the .ipynb notebook in Google Colab.
2. Upload or connect the required dataset.
3. Run the notebook cells from top to bottom.
4. Review the generated analysis, visualizations, insights, and recommendations.

### Option 2: Local Jupyter Notebook

Install the required libraries:

pip install -r requirements.txt

Then open:

PrathamMeena_CustomerBehavior_EcommerceAnalytics.ipynb

using Jupyter Notebook or JupyterLab.

## Author

Pratham Meena

B.Tech Computer Science & Engineering

## Internship

AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 | BharatCares

---

This project is intended for educational, analytical, and portfolio purposes.
