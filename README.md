# Global Superstore Data Analysis

Business-focused exploratory data analysis of a multi-year global retail dataset, using Python to identify the drivers behind sales, profitability, customer behavior, product performance, and regional trends.

## Business Goal

The objective is to turn transactional retail data into useful business conclusions. The analysis focuses on questions such as:

- Which markets and product categories generate the strongest revenue?
- Where is profitability being lost despite strong sales?
- Which customer segments contribute most to performance?
- How do discounts, shipping costs, and fulfillment choices affect margins?
- What seasonal or geographic patterns should decision-makers pay attention to?

## Analysis Workflow

### 1. Data Preparation

- Validate data types and column consistency
- Standardize date fields
- Inspect missing values
- Review duplicate and invalid records
- Prepare financial and categorical fields for analysis

### 2. Descriptive Analytics

- Total sales and profit
- Profit margin
- Order volume
- Average order metrics
- Category and sub-category contribution

### 3. Geographic Analysis

Performance is compared across countries, regions, and major markets to surface differences in sales scale and profitability.

### 4. Product Analysis

The project evaluates category and sub-category performance to distinguish high-revenue products from genuinely high-margin products.

### 5. Customer & Shipping Analysis

Customer segments and shipping methods are evaluated alongside financial outcomes to identify operational patterns that influence profitability.

### 6. Trend Analysis

Monthly and yearly views are used to identify growth, seasonality, and shifts in business performance over time.

## Tech Stack

| Area | Tools |
| --- | --- |
| Language | Python |
| Data wrangling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Analysis environment | Jupyter Notebook |

## Dataset

The Global Superstore dataset contains order-level information across multiple markets, including:

- order and shipping dates
- customer segment and geography
- product category and sub-category
- sales and quantity
- discounts
- profit
- shipping cost

## Key Analytical Themes

- Revenue does not necessarily equal profitability
- Discounting can materially change category economics
- Shipping cost is an important operational variable
- Regional scale should be interpreted alongside margin quality
- Segment and product mix affect overall business performance

The goal of the notebook is to support these conclusions with data rather than treat them as assumptions.

## Run Locally

```bash
git clone https://github.com/ShadyMayez/Global-Superstore-Data-Analysis.git
cd Global-Superstore-Data-Analysis
pip install -r requirements.txt
```

Open the project notebook in Jupyter and ensure the dataset is available at the path referenced by the notebook.

## Skills Demonstrated

- Data cleaning and validation
- Exploratory data analysis
- KPI design
- Business-oriented visualization
- Trend and segmentation analysis
- Translating analytical results into actionable findings

---

Built by [ShadyMayez](https://github.com/ShadyMayez).