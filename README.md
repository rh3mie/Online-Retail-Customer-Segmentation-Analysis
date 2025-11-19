# Online-Retail-Customer-Segmentation-Analysis

By Rhey Mar De Vera

### Project Overview
This project aims to identify different customer groups based on their purchasing behavior to help this company create marketing strategies to improve customer retention and increase revenue. This project will also look into the general analysis of the store's business, acquiring insights such as sales trends, customer trends, popular products, and performance over time. 

Libraries used: ```pandas```, ```numpy```, ```plotly```, ```matplotlib```, ```seaborn```

### Data
The dataset I will be using is a transactional data set containing transactions occurring between  2009-2011, for a UK-based online retail store. The link for the original data set can be accessed [here](https://archive.ics.uci.edu/dataset/352/online+retail). 

```online.csv``` in this repo is a compressed version of the data from [Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci), but I used the original data from UCI, which was too big to upload to GitHub.

The data set consists of 8 variables:
- **InvoiceNo**: A 6-digit integral number assigned to each transaction. Code starting with 'c' indicates a cancellation. 
- **StockCode**: A 5-digit integral number uniquely assigned to each distinct product
- **Description**: The product name
- **Quantity**: The amount of each product per transaction
- **InvoiceDate**: The date and time each transaction was generated
- **UnitPrice**: Product Price per unit
- **CustomerID**: Unique 5-digit IDs uniquely assigned to each customer
- **Country**: The name of the country where the customer purchased an item

### Key Steps
1. Data Cleaning and Preparation

- Inspected the data properties, looking for any null or duplicate values and removing them promptly. Also removed negative and zero values, since this project focuses on customer purchase behavior. 

2. Sales Analysis

- Use cleaned transaction data to create visualizations for sales insights, including item sales, customer revenue, country sales, etc.

3. 

