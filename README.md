## Supermart-Grocery-Sales-Analysis

The Supermart Grocery Sales Analysis project is a comprehensive exploration of sales data from a supermarket, aimed at uncovering key trends, insights, and customer behavior patterns. By analyzing sales distribution across product categories, seasonal trends, and regional performance, this project provides actionable recommendations to optimize sales strategies, improve inventory management, and enhance customer targeting.

## Dataset Information:

* Source: The dataset contains detailed information about supermarket orders, including Order ID, Customer Name, Category, Sub Category, City, Order Date, Region, Sales, Discount, and Profit.
* Size: The dataset consists of 9,994 rows and 12 columns, covering sales data over multiple years.
* Time Period: The data spans several years, allowing for analysis of long-term trends and seasonal variations.

Key Variables:
* Sales: The total sales amount for each order.
* Category: Product categories such as Eggs, Meat & Fish, Snacks, Bakery, Oils & Masala, and more.
* Region: Geographic regions including East, West, North, and South.
* Order Date: The date of each order, used to analyze monthly and yearly trends.

## Key Objectives:

1. Analyze Sales Trends: Examine overall sales trends and revenue distribution over time to identify growth patterns and seasonal fluctuations.
2. Identify Top-Performing Categories: Determine which product categories generate the highest sales and profits, and understand consumer preferences.
3. Understand Seasonal Variations: Investigate how sales vary across different months and seasons, particularly during festive and holiday periods.
4. Provide Data-Driven Recommendations: Offer actionable insights to improve marketing strategies, inventory planning, and customer engagement.

## Key Questions:

1. What are the overall sales trends and revenue distribution across different product categories?
2. Which product categories perform the best and the worst in terms of sales?
3. What are the seasonal variations in sales?
4. How do sales vary by region, and which regions have higher or lower performance?
5. How have sales and profitability evolved over the years?
6. What are the top-performing cities in terms of total sales?
7. How can we improve sales for underperforming categories or regions?
8. What factors (features) most impact sales predictions?
9. What recommendations can be made to optimize sales and inventory management based on the analysis?

## Methodology:
* Data Loading & Cleaning: The dataset, containing details about orders, categories, sales, and order dates, was loaded and cleaned. Missing values were handled using forward fill (ffill), and duplicate entries were removed.
* Time-Based Analysis: The "Order Date" column was converted to datetime format, and time-based features (Month, Year) were extracted to analyze trends over time.
* Exploratory Data Analysis (EDA): Various visualizations, including box plots, bar charts, line plots, and heatmaps, were used to explore sales distribution, seasonal trends, and correlations between variables.
* Feature Engineering: Categorical variables were encoded using Label Encoding, and new features like Sales_Discount and Sales_Profit were created to enhance the dataset.
* Model Building & Evaluation: A Random Forest Regressor model was trained to predict sales, achieving high accuracy (R² ≈ 0.9999). The model's performance was evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics.

## Key Insights:
1. Top Categories: Eggs, Meat & Fish and Snacks are the highest revenue-generating categories, while Oils & Masala and Household Items underperform.
2. Seasonal Trends: Sales peak during September, November, and December due to festive and holiday shopping, and dip in January and February.
3. Regional Performance: The East and West regions show higher sales compared to the North and South, indicating regional disparities in consumer spending.
4. Yearly Growth: Sales exhibit consistent year-over-year growth, with significant spikes during peak months.
5. Category Variability: While all categories show growth, Bakery maintains consistent demand, whereas Snacks experience more fluctuations.

## Recommendations:
1. Seasonal Marketing: Focus marketing efforts on high-sales months like September, November, and December to maximize revenue.
2. Inventory Optimization: Stock high-demand categories like Eggs, Meat & Fish and Snacks during peak seasons to avoid stockouts.
3. Boost Underperforming Categories: Use promotions and bundling strategies to increase sales of low-performing categories like Oils & Masala.
4. Regional Strategies: Tailor marketing and inventory strategies to regional preferences, particularly in underperforming regions like the North and South.
5. Personalized Marketing: Leverage customer purchase data to create personalized offers and loyalty programs.

## Conclusion:
The Supermart Grocery Sales Analysis project provides valuable insights into supermarket sales trends, enabling businesses to make data-driven decisions for optimizing sales strategies and improving profitability. By understanding seasonal patterns, category performance, and regional dynamics, the supermarket can enhance its market positioning and customer satisfaction, ensuring sustained growth in a competitive retail environment.
