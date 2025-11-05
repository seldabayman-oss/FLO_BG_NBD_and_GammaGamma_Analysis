# FLO_BG_NBD_and_GammaGamma_Analysis
Phyton Data Analysis

## Customer Lifetime Value (CLTV) Prediction and Analysis 🚀

Overview This project focuses on predicting customer lifetime value (CLTV) using advanced statistical and machine learning models. The analysis aims to provide actionable insights for a business by identifying its most valuable customers and forecasting future sales.

Key highlights of the project include:

Top 10 customers expected to make the most purchases within 1 month. Total expected sales for the entire company over the next 3 months. Customer segmentation based on purchasing behavior.

## Dataset 📊

The dataset used for this analysis is the Online Retail II dataset. It contains transactional data for a UK-based online retailer, including customer purchase history between 2009 and 2011.

## Methodology 🧠

Data Preparation and Cleaning:

Removed missing or invalid entries (e.g., Customer ID, InvoiceDate). Filtered for customers with at least one repeat purchase (frequency > 1). Calculated key CLTV metrics: Recency: Time since the customer's last purchase. T: Customer's total lifespan (in weeks). Frequency: Number of repeat purchases. Monetary Value: Average revenue per purchase.

Modeling:

BG/NBD Model (Beta Geo Fitter): Used to predict customer purchase frequency over time. Gamma-Gamma Model: Estimated the monetary value of customers based on past transactions. Implemented with the lifetimes Python library for CLTV prediction.

## Analysis:

Forecasted expected purchases for each customer over 1 and 3-month periods. Ranked customers based on their predicted contribution to revenue. Aggregated predictions to calculate company-wide sales estimates.

## Results 📈

Insights Top 10 Customers: The 10 customers expected to make the most purchases within the next month were identified, enabling the business to focus marketing and retention efforts on them.

Company-Wide Forecast: The total number of expected sales over the next 3 months is [X] (calculated using the BG/NBD model).

Customer Segmentation: Customers were categorized into high-value and low-value segments based on their predicted CLTV, offering targeted business strategies for each group.

Key Metrics: Metric Value Total Customers Analyzed [X] Top 10 Customer Predictions [X Purchases] Company-Wide 3-Month Sales [X Purchases]

## Tools and Libraries 🛠️

Python pandas for data manipulation lifetimes for CLTV modeling (BG/NBD and Gamma-Gamma models) matplotlib and seaborn for visualizations

## Business Case 🏢

This analysis is ideal for businesses looking to:

Optimize marketing efforts by identifying high-value customers. Forecast revenue trends and sales for future periods. Improve retention strategies through customer segmentation.

How to Reproduce the Analysis 🖥️

## Clone the repository:

git clone https://github.com/your-username/cltv-analysis.git cd cltv-analysis Install the required libraries:

pip install -r requirements.txt Run the analysis notebook or script:

python cltv_analysis.py

## Conclusion 🌟

The CLTV analysis provides critical insights into customer behavior and revenue forecasting, allowing businesses to allocate resources effectively and maximize profitability. The use of statistical models ensures reliable predictions and scalable solutions.
