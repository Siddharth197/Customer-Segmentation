Customer Segmentation, Market Basket Analysis & Sales Forecasting

Project Overview

This project analyzes an Online Retail dataset to gain insights into customer behavior, identify market segments, and forecast sales trends. The key components include:

Customer Segmentation (RFM Analysis + K-Means Clustering)

Market Basket Analysis (Apriori Algorithm for product recommendations)

Sales Forecasting (ARIMA Time Series Model)

Dataset Information

The dataset contains transaction records from an online retail store with the following columns:

InvoiceNo: Unique transaction ID

StockCode: Product identifier

Description: Product name

Quantity: Number of items purchased

InvoiceDate: Date & time of purchase

UnitPrice: Price per item

CustomerID: Unique identifier for customers

Country: Country where the purchase was made

Installation

To run this project, install the required Python packages using:

pip install pandas numpy matplotlib seaborn scikit-learn mlxtend statsmodels

Steps & Methodology

1. Data Preprocessing

Remove missing values

Filter out negative quantities & prices

Compute Monetary column as Quantity * UnitPrice

2. Customer Segmentation (RFM Analysis + K-Means)

Recency: Days since last purchase

Frequency: Total number of purchases

Monetary: Total money spent

Perform K-Means clustering to group customers into different segments

3. Market Basket Analysis (Apriori Algorithm)

Convert transaction data into a basket format

Use Apriori Algorithm to extract product association rules

Identify frequently bought-together items

4. Sales Forecasting (ARIMA Model)

Aggregate monthly sales data

Fit an ARIMA time series model to predict future sales

Visualize the forecasted sales trend

Running the Code

Run the Jupyter Notebook file to execute all the steps:

jupyter notebook Customer_Segmentation_Analysis.ipynb

Output & Insights

Customer Segmentation: Identify high-value customers

Product Recommendations: Suggest frequently purchased items

Sales Trends: Predict future revenue

Contribution

Feel free to fork this repository, improve the analysis, and submit pull requests!

License

This project is open-source under the MIT License.
