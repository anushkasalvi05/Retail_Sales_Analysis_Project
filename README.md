# Retail Sales Analysis and Prediction

This project contains a **Jupyter notebook** for performing **Retail Sales Analysis and Prediction**. It explores sales patterns, identifies key trends in customer behavior, and applies time-series forecasting to predict future sales. The analysis includes **data preprocessing**, **market basket analysis**, and **model evaluation**, focusing specifically on the **UK market** to derive meaningful insights.

## Project Overview
This notebook uses retail sales data to identify patterns and predict future sales. We focus on:
- **Data Preprocessing**: Cleaning and preparing the data.
- **Market Basket Analysis**: Identifying frequently purchased items together.
- **Time-Series Forecasting**: Using the **SARIMAX model** to predict sales over time.

The Market Basket primarily covers sales transactions from the **UK market**, as it represents the largest customer base, as seen in the accompanying graphs.

### Main Features:
1. **Preprocessing**:
    - Handling missing data
    - Removing duplicate transactions
    - Handling cancelled transactions
2. **Market Basket Analysis**:
    - Use of the **Apriori algorithm** to identify frequently purchased items together.
3. **Time-Series Analysis**:
    - **SARIMAX model** for predicting future sales based on historical data.
4. **Visualizations**:
    - Bar charts, histograms, and pie charts to visualize data patterns and trends.
    - Forecasting graphs to predict future sales.

## Dataset

**Note**: The dataset used for this analysis is included in this repository as the file **`data.zip`**. It contains retail sales data that has been concatenated from multiple years of transaction records. 

### Data Description:
- **Invoice**: Unique invoice number.
- **StockCode**: Unique product code.
- **Description**: Product description.
- **Quantity**: Quantity of products purchased.
- **InvoiceDate**: Date and time of the transaction.
- **Price**: Price of the product.
- **Customer ID**: Unique identifier for the customer.
- **Country**: Country where the purchase was made.

You can access the dataset directly in the repository by downloading the **`data.zip`** file.

## Requirements

To run this notebook, you'll need to have Python and the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- mlxtend (for the Apriori algorithm)

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn statsmodels mlxtend

