# Superstore Sales Dataset

## Overview
This dataset represents fictional sales data from a global superstore. It includes detailed information about customer orders, shipping logistics, and product-level sales. This dataset is frequently used in data analysis, business intelligence, and machine learning projects to practice tasks such as data preprocessing, visualization, and modeling.

## Dataset Structure

The dataset is formatted as a tab-separated values (TSV) file with the following columns:

| Column Name      | Description |
|------------------|-------------|
| `Row ID`         | Unique identifier for each row |
| `Order ID`       | Unique ID associated with each order |
| `Order Date`     | The date when the order was placed (`MM/DD/YYYY`) |
| `Ship Date`      | The date when the order was shipped (`MM/DD/YYYY`) |
| `Ship Mode`      | The mode of shipping (e.g., Second Class, Standard Class) |
| `Customer ID`    | Unique identifier for each customer |
| `Customer Name`  | Full name of the customer |
| `Segment`        | Customer segment (`Consumer`, `Corporate`, `Home Office`) |
| `Country`        | Country of the customer (All entries are `United States`) |
| `City`           | City of the customer |
| `State`          | State of the customer |
| `Postal Code`    | Postal/ZIP code of the customer |
| `Region`         | Sales region (e.g., `West`, `South`) |
| `Product ID`     | Unique identifier for each product |
| `Category`       | Main product category (`Furniture`, `Office Supplies`, etc.) |
| `Sub-Category`   | Sub-category under each product category |
| `Product Name`   | Name of the product sold |
| `Sales`          | Sales amount in USD |
| `Quantity`       | Quantity of products sold |
| `Discount`       | Discount applied (range: `0` to `1`) |
| `Profit`         | Profit from the sale in USD |

## Sample Data

Here are a few example rows from the dataset:

| Row ID | Order ID        | Order Date | Ship Date  | Ship Mode     | Customer Name     | Segment   | State      | Category       | Sub-Category | Product Name                                                 | Sales   | Quantity | Discount | Profit  |
|--------|------------------|------------|------------|---------------|-------------------|-----------|------------|----------------|---------------|--------------------------------------------------------------|---------|----------|----------|---------|
| 1      | CA-2016-152156   | 11/8/2016  | 11/11/2016 | Second Class  | Claire Gute       | Consumer  | Kentucky   | Furniture       | Bookcases     | Bush Somerset Collection Bookcase                            | 261.96  | 2        | 0        | 41.91   |
| 2      | CA-2016-152156   | 11/8/2016  | 11/11/2016 | Second Class  | Claire Gute       | Consumer  | Kentucky   | Furniture       | Chairs        | Hon Deluxe Fabric Upholstered Stacking Chairs                | 731.94  | 3        | 0        | 219.58  |
| 3      | CA-2016-138688   | 6/12/2016  | 6/16/2016  | Second Class  | Darrin Van Huff   | Corporate | California | Office Supplies | Labels        | Self-Adhesive Address Labels for Typewriters by Universal    | 14.62   | 2        | 0        | 6.87    |

## Use Cases

This dataset is ideal for:
- Data preprocessing and cleaning exercises
- Exploratory Data Analysis (EDA)
- Data visualization projects
- Regression and classification modeling (with additional feature engineering)
- Learning data manipulation with Excel, Python (Pandas), or R

## License

This dataset is fictional and provided for academic, educational, and demonstration purposes only.
