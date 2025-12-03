# retail-sales-analysis
Retail sales analytics project in Python

# Retail Sales & Profit Analysis

## Objective
Analyze retail sales data to identify profit drivers, loss-making categories,
regional performance, and growth trends so that management can take better
data-driven decisions.

## Dataset
- Sample Superstore sales dataset (from Kaggle)
- Contains order-level details: Orders, Customers, Region, Category, Sales, Profit, etc.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Analysis Performed
- Category & sub-category wise sales and profit
- Region and state level performance
- Customer segment analysis
- Top and bottom customers by profit
- Monthly sales trend (time series)
- Profit margin analysis (Profit / Sales)

## Key Insights
- Technology and Office Supplies have the highest profit margins.
- Furniture generates good revenue but very poor margins.
- West and East regions are the best performers.
- States like Texas and Illinois are strongly loss-making.
- A small group of customers contributes a large share of total profit.
- Sales show clear seasonality and an overall upward trend.

## Advanced Analysis – Profit Margin
Instead of looking only at revenue, a profit margin column was created:
> Profit Margin = Profit / Sales

This helped reveal hidden financial leakage where high sales still produced
negative or very low profit, especially in some states and categories.

## Business Recommendations
- Focus more on high-margin categories (Technology, Office Supplies).
- Revisit pricing and discount strategy for Furniture, especially Tables.
- Audit operations and pricing in loss-making states like Texas and Illinois.
- Strengthen loyalty strategies for high-profit customers.
- Use seasonality patterns to plan inventory and marketing before peak months.

## Outcome
This project demonstrates end-to-end business analytics:
data cleaning, exploratory data analysis, visualization, margin analysis, and
strategy-focused recommendations using Python.
