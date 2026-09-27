# Flipkart Product Price Analysis

An e-commerce data analytics project analyzing 20,000 Flipkart product listings to understand pricing, discounts, categories, brands, ratings, and price outliers.

## Project Overview

The project analyzes the Flipkart product catalog to identify useful business insights related to:

- Product category distribution
- Retail and discounted prices
- Discount percentages
- Price distributions
- Price tiers
- Brand listing volume
- Discount vs. rating relationship
- Price outliers

The analysis uses SQL as the primary analytical layer, with Python and DuckDB for data processing and Streamlit + Plotly for the interactive dashboard.

## Dataset

**Dataset:** Flipkart Products  
**Source:** [Kaggle - Flipkart Products](https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products)

- 20,000 product listings
- 15 columns

Important columns include:

- `product_name`
- `product_category_tree`
- `retail_price`
- `discounted_price`
- `product_rating`
- `brand`

The raw CSV file is not included in this repository because of its large file size.

To download the dataset, run:

```bash
python Python/download_data.py
