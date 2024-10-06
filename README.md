# CustomerSegmentation-ML
# Online Retail Dataset Analysis

## Overview

This project provides an in-depth analysis of the **Online Retail Dataset**, which consists of 541,909 transactions made by customers across various countries. The dataset includes 8 columns: 'InvoiceNo', 'StockCode', 'Description', 'Quantity', 'InvoiceDate', 'UnitPrice', 'CustomerID', and 'Country'. Our primary focus is on understanding customer behavior, identifying purchasing trends, and providing actionable business insights.

### Key Objectives
- Conduct Exploratory Data Analysis (EDA) to uncover patterns in customer behavior and purchasing trends.
- Visualize relationships between different attributes and detect outliers in the data.
- Segment customers using clustering techniques to provide marketing and engagement strategies.
- Provide recommendations to enhance customer retention and optimize business operations.

## Dataset Information

- **Total Records**: 541,909
- **Columns**:
  - `InvoiceNo`: Unique identifier for each transaction.
  - `StockCode`: Product code.
  - `Description`: Product name.
  - `Quantity`: Number of items purchased.
  - `InvoiceDate`: Date of purchase.
  - `UnitPrice`: Price of each item.
  - `CustomerID`: Unique customer identifier.
  - `Country`: Country where the transaction occurred.

## Key Findings

1. **Quantity and UnitPrice Distribution**:
   - Both 'Quantity' and 'UnitPrice' are right-skewed, meaning a large number of transactions involve small quantities or lower-priced items, with a few high-value transactions indicating wholesale customers.
   
2. **Outliers Detection**:
   - Several outliers were detected in the dataset, which may require further investigation to maintain data integrity.

3. **Customer Segmentation**:
   - Using clustering analysis, we identified **3 distinct customer segments**:
     - **Cluster 0 (At-Risk/Lapsed Customers)**: Customers who haven’t purchased in a while and may need re-engagement strategies.
     - **Cluster 1 (Champions/Loyal Customers)**: Frequent purchasers who can be targeted for loyalty programs and exclusive deals.
     - **Cluster 2 (Potential Loyalists/Promising Customers)**: Customers who show potential for higher engagement and may benefit from personalized recommendations and promotions.

## Recommendations

Based on the analysis, the following strategies are recommended:
- **Customer Engagement**:
  - Implement re-engagement campaigns for at-risk customers with incentives like discounts and feedback surveys.
  - Offer loyalty programs, referral programs, and exclusive deals for loyal customers to maintain high levels of engagement.
  - Provide personalized communication and product recommendations for promising customers.
  
- **Inventory Management**:
  - Monitor stock levels of popular products to avoid shortages and maximize sales.
  
- **International Expansion**:
  - Explore potential markets for international expansion based on growing customer bases in countries with significant purchasing activity.

## Visualizations

Various visualizations, including histograms, scatter plots, and clustering plots, were generated to better understand the data distribution, attribute relationships, and customer segments. These visualizations helped reveal key patterns and outliers.

## Tools and Libraries Used
- **Python**
- **Pandas** for data manipulation and cleaning.
- **Matplotlib** and **Seaborn** for data visualization.
- **Scikit-learn** for clustering and segmentation analysis.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-retail-analysis.git
