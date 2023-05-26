# Time-Series-For-Pakistan-Largest-Ecommerce

This dataset contains half a million e-commerce orders in Pakistan from March 2016 to August 2018. The dataset contains detailed information about the orders, including item details, shipping method, payment method, product categories, date of order, SKU, price, quantity, total, and customer ID.

### EDA and Analysis
The following EDA and analysis was performed on the dataset:

The shape of the dataset was checked.
The first few rows of the dataset were looked at.
The total number of orders was calculated.
The total revenue was calculated.
The average order value was calculated.
The most popular product category was identified.
The most popular payment method was identified..
A bar chart of the number of orders by product category was plotted.
A line chart of the total revenue over time was plotted.
### Feature Engineering
The following features were engineered:

The order date was converted to a datetime object.
The Total Quantity was calculated as the total qunatities of products that have been ordered.

### Time Series Analysis
The following time series analysis was performed:

ARIMA and SARIMAX models were fit to the Total Quantity data.
The forecast has been impelmented to both models.
