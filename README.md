# DataAnalysis
Retail Sales and Customer Segmentation

# Overview
This project focuses on retail sales analysis and customer segmentation using the RFM (Recency, Frequency, Monetary) model. We utilize Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn to process data, generate insights, and apply K-Means clustering for customer segmentation.

# Features:
Data Cleaning & Preprocessing: Handles missing values, removes invalid transactions, and computes total purchase amounts.
Sales Analysis: Monthly revenue trends, best-selling products, and top-performing countries.
RFM Analysis: Calculates Recency, Frequency, and Monetary values for each customer.
Customer Segmentation: Uses K-Means clustering to classify customers into different groups based on RFM metrics.
Data Visualization: Generates informative graphs to understand sales trends and customer behavior.

# Dataset
The dataset used is 'Online Retail.xlsx', which contains transactional data from an e-commerce store.
The dataset includes key columns:
InvoiceNo: Transaction ID
StockCode: Product identifier
Description: Product name
Quantity: Number of units purchased
InvoiceDate: Date and time of purchase
UnitPrice: Price per unit
CustomerID: Unique customer identifier
Country: Customer location

# Data Processing & Analysis

1️ Data Cleaning
Removes missing CustomerID values.
Converts InvoiceDate to a DateTime format.
Filters out negative or zero values for Quantity and UnitPrice.
Removes canceled transactions (InvoiceNo starting with 'C').

2️ Sales Analysis
Monthly Sales Trend: Line plot showing revenue trends over time.
Top 10 Best-Selling Products: Bar chart highlighting the most purchased items.
Top 10 Countries by Sales: Bar chart showcasing revenue distribution by country.

3️ RFM Calculation
Recency: Number of days since the customer’s last purchase.
Frequency: Number of unique transactions made by the customer.
Monetary: Total amount spent by the customer.

4️ Customer Segmentation (K-Means Clustering)
Scales RFM values using StandardScaler.
Uses the Elbow Method to determine the optimal number of clusters.
Applies K-Means clustering (k=4) to segment customers.
Assigns segment labels:
Loyal Customers
At Risk Customers
High Value Customers
Churned Customers
Visualizes customer segmentation using a scatter plot.

# Installation & Usage
Required libraries: pandas, numpy, matplotlib, seaborn, sklearn
Upload the dataset ('Online Retail.xlsx').
The segmented customer data is saved as 'RFM_Clusters.csv'.

# Visualizations
1️ Monthly Sales Trend
Shows revenue fluctuations over time to identify peak and low sales periods.
2️ Best-Selling Products
Identifies which products drive the most sales.
3️ RFM Distributions
Histograms of Recency, Frequency, and Monetary values to understand customer behavior.
4️ Customer Segmentation Plot

Clusters customers into different segments based on their RFM values.




