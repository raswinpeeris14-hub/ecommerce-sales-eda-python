# E-Commerce Sales Performance Analysis Using Python

## Project Overview

This project performs exploratory data analysis on an e-commerce sales dataset using Python.

The analysis focuses on sales performance, revenue, profit, products, categories, regions, payment methods, delivery time, and order status.

## Business Objective

The objective of this project is to identify:

- Top-performing products and categories.
- Highest-revenue regions.
- Monthly sales and profit trends.
- Popular payment methods.
- Loss-making orders.
- The relationship between discount and profit.
- Delivery and order-status patterns.

## Dataset

The dataset contains 1,200 e-commerce orders and 14 columns.

Important columns include:

- `order_id`
- `order_date`
- `customer_id`
- `product`
- `category`
- `region`
- `quantity`
- `unit_price`
- `discount`
- `revenue`
- `profit`
- `payment_method`
- `delivery_days`
- `order_status`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### Data Cleaning

- Checked missing values.
- Checked duplicate rows.
- Converted `order_date` into datetime format.
- Checked data types and unique values.

### Feature Engineering

Created the following features:

- Year
- Month
- Quarter
- Profit margin
- Loss indicator
- Delivery group

### Exploratory Data Analysis

Analyzed:

- Revenue by product.
- Profit by product.
- Revenue and profit by category.
- Revenue by region.
- Monthly revenue and profit.
- Order-status distribution.
- Payment-method usage.
- Discount versus profit.
- Quantity versus revenue.
- Correlation between numerical variables.

## Key Findings

- Total revenue was 255,856.75.
- Total profit was 43,871.75.
- Overall profit margin was approximately 17.15%.
- Electronics was the highest-revenue category.
- Monitor was the top-performing product by revenue.
- North was the highest-performing region.
- June had the highest monthly revenue.
- UPI was the most frequently used payment method.
- There were 49 loss-making orders.
- Cash on Delivery had the longest average delivery time.

## How to Run the Project

Clone the repository:

```bash
git clone [https://github.com/YOUR_USERNAME/ecommerce-sales-eda-python.git](https://github.com/YOUR_USERNAME/ecommerce-sales-eda-python.git)
```

Open the project folder:

```bash
cd ecommerce-sales-eda-python
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook:

```text
notebooks/ecommerce_sales_eda.ipynb
```

## Project Structure

```text
ecommerce-sales-eda-python/
├── data/
│   └── ecommerce_sales_dataset.csv
├── notebooks/
│   └── ecommerce_sales_eda.ipynb
├── outputs/
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Improvements

- Build an interactive Power BI dashboard.
- Add customer segmentation.
- Create a sales forecasting model.
- Analyze customer lifetime value.
- Add automated tests for data quality.
