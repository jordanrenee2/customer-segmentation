# E-Commerce Customer Segmentation Analysis

Customer segmentation using RFM analysis and K-means clustering to identify high-value customer segments and develop targeted marketing strategies.

## Project Overview

This project analyzes behavioral and transactional data from 10,000 e-commerce customers to identify distinct segments based on their purchase patterns and engagement levels. Using RFM (Recency, Frequency, Monetary) analysis and K-means clustering, I segmented customers into four actionable groups and developed tailored marketing strategies for each.

## Key Features

- **Data Cleaning & Preprocessing**: Handled outliers, standardized features, and engineered engagement metrics
- **Exploratory Data Analysis**: Visualized customer behavior patterns and feature correlations
- **RFM Analysis**: Leveraged industry-standard metrics to evaluate customer value
- **K-Means Clustering**: Segmented customers into 4 distinct groups using unsupervised learning
- **Business Insights**: Translated technical findings into actionable marketing recommendations

## Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib & seaborn** - Data visualization
- **scikit-learn** - Machine learning and clustering

## Customer Segments Identified

1. **VIP Champions (9.7%)**: Highest-value customers with frequent recent purchases and maximum spend
2. **High-Value Loyalists (21.9%)**: Strong performers with consistent purchasing and high engagement
3. **Promising Regulars (10.8%)**: Mid-tier customers with growth potential
4. **At-Risk Customers (57.6%)**: Largest segment requiring re-engagement strategies

## Project Structure
```
customer-segmentation/
├── ecommerce_segmentation.ipynb    # Main analysis notebook
├── data/
│   ├── ecommerce_user_segmentation.csv
│   ├── ecommerce_user_behavior_cleaned.csv
│   └── ecommerce_segmented_customers.csv
├── images/                          # Generated visualizations
├── README.md
└── requirements.txt
```


## Key Insights

- **57.6% of customers are at-risk**, presenting a significant opportunity for win-back campaigns
- **VIP Champions generate disproportionate revenue** despite being less than 10% of the customer base
- **Strong correlation between engagement metrics and customer value**, validating the importance of session tracking
- **Cart abandonment rates vary significantly by segment**, suggesting the need for differentiated recovery strategies

## Business Recommendations

- Implement VIP loyalty programs to retain top 10% of customers
- Launch targeted win-back campaigns for at-risk segment
- Develop tiered marketing automation based on segment characteristics
- Track segment migration quarterly to measure campaign effectiveness

## Future Enhancements

- Predict customer lifetime value (CLV) for each segment
- Build classification model to assign new customers to segments
- Incorporate time-series analysis to track segment evolution
- A/B test marketing strategies by segment

