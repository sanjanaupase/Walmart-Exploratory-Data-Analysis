# Walmart-Exploratory-Data-Analysis

Perform Exploratory Data Analysis (EDA) on the Walmart dataset to gain insights into sales and customer behavior. The dataset contains information about orders, customers, products, and sales quantity. The main objective is to identify patterns, trends, and top-performing segments, products, and customers to help the sales and marketing team improve their strategies and increase sales and revenue.

## Getting Started

To run this analysis, you will need the following libraries installed:

- pandas
- matplotlib

You can install these libraries using pip:

```bash
pip install pandas matplotlib
```

Make sure you have the 'Walmart_data.csv' file available in the specified location (`C:/Users/User/Desktop/portfolio/`). If your file is in a different location, update the file path accordingly.

## Jupyter Notebook

Open the Jupyter Notebook 'Walmart_Data_Analysis.ipynb' to view the code and run the data analysis.

## Data Preprocessing

The data is loaded into a pandas DataFrame, and the 'Order Date' column is converted to a datetime format to facilitate date-based analysis.

## Questions and Visualizations

The analysis covers the following questions:

1. **Most profitable categories:** Identify the top 10 categories based on the total quantity sold.
2. **Top-performing states:** Determine the top 5 states with the highest quantity sold and visualize the results on a bar chart.
3. **Top segments by quantity sold:** Find the top segments based on the total quantity sold and visualize the results on a bar chart.
4. **Top customers:** Identify the top 5 customers with the highest quantity sold and visualize the results on a bar chart with quantity sold displayed on top of each bar.
5. **Products with consistently high demand:** Discover the top 5 products with consistently high demand throughout the year and visualize the results on a bar chart with average quantity sold.
6. **Categories with consistently high demand:** Analyze the top 5 categories with consistently high demand throughout the year and visualize the results on a bar chart with average quantity sold.
7. **Sub-Categories with consistently high demand:** Explore the top 5 sub-categories with consistently high demand throughout the year and visualize the results on a bar chart with average quantity sold.
8. **Top customers by order count:** Find the top 10 customers based on the count of orders and visualize the results on a bar chart with the number of orders displayed on top of each bar.
9. **Sales performance over the years:** Analyze the sales performance over the years and visualize it on a line plot.
10. **Sales trend over time:** Explore the sales trend over time by month and visualize it on a line plot.
11. **Seasonal sales trends:** Observe the seasonal sales trends and visualize them on a line plot.

The visualizations will provide valuable insights into the sales trends and customer behavior, helping Walmart's sales and marketing team make data-driven decisions to improve their strategies and increase sales and revenue.
