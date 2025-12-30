# Global Superstore Sales Analysis

## Project Overview and Purpose
This project performs an in-depth Exploratory Data Analysis (EDA) on the Global Superstore dataset, a multi-year retail dataset containing sales and profit information. The goal is to identify key business drivers, profitable product categories, and geographical performance trends to provide actionable business insights.

## Key Technologies and Libraries
- **Language**: Python
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook

## Data and Methodology
### Dataset
The analysis is based on the **Global Superstore Dataset**, which includes:
- **Order Details**: Order ID, Order Date, Ship Date, Ship Mode.
- **Customer Info**: Segment, City, State, Country, Region.
- **Product Details**: Category, Sub-Category, Product Name.
- **Financial Metrics**: Sales, Quantity, Discount, Profit, Shipping Cost.

### Analysis Workflow
1. **Data Loading & Cleaning**: Standardizing date formats, handling missing postal codes, and verifying data types for monetary values.
2. **Descriptive Analytics**: Calculating total sales, profit margins, and order volumes.
3. **Geographical Analysis**: Mapping sales and profit distribution across global markets (APAC, EU, US, etc.).
4. **Product Analysis**: Identifying high-performing categories (e.g., Technology) versus underperforming sub-categories (e.g., Tables).
5. **Trend Analysis**: Visualizing monthly and yearly sales growth to identify seasonal patterns.



## Results and Insights
- **Profitability**: Technology is typically the most profitable category, while Furniture often sees lower margins due to high shipping costs and discounts on sub-categories like Tables.
- **Top Markets**: The Asia-Pacific (APAC) and US markets contribute the highest revenue.
- **Customer Segments**: The "Consumer" segment usually accounts for the largest share of total sales.
- **Shipping**: Analysis of ship modes reveals correlations between shipping speed and profit retention.

## How to Run
1. Ensure the `Global Superstore.csv` (or Excel equivalent) is in the same directory as the notebook.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
