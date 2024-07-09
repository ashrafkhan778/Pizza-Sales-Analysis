![image](https://github.com/ashrafkhan778/Pizza-Sales-Analysis/assets/149621365/b71b043e-d7e6-4c2a-8bcc-43dedc3f3aa3)# Pizza Sales Analysis'

# Overview

The Pizza Sales Project is a data analysis and visualization project aimed at analyzing and visualizing sales data from a fictional pizza restaurant chain. 
This project utilizes SQL for data extraction and transformation and Power BI for data visualization.The goal of this project is to provide insights and actionable information to help the pizza restaurant chain optimize its operations, improve sales, and enhance customer satisfaction.
About DataSet
This pizza sales dataset make up 12 relevant features:

order_id: Unique identifier for each order placed by a table

order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)

pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price

quantity: Quantity ordered for each pizza of the same type and size

order_date: Date the order was placed (entered into the system prior to cooking & serving)

order_time: Time the order was placed (entered into the system prior to cooking & serving)

unit_price: Price of the pizza in USD

total_price: unit_price * quantity

pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)

pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price

pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)

pizza_name: Name of the pizza as shown in the menu

# Project Components
1. # Data Acquisition
The project begins with the acquisition of raw sales data. This data may include information such as customer orders, product details, order dates, and transaction amounts. Data can be obtained from various sources, including databases, CSV files, or other data storage systems.

2. # Data Transformation with SQL
SQL (Structured Query Language) is used to clean, filter, and transform the raw data into a format suitable for analysis. This may involve tasks such as joining tables, aggregating data, handling missing values, and creating new calculated fields.

3. # Data Analysis
Once the data is prepared, various SQL queries are written to perform in-depth data analysis. This may include:

Identifying top-selling pizza flavors.
Analyzing sales trends over time.
Evaluating customer demographics and preferences.
Calculating average order values.
Assessing the performance of individual restaurant locations.

4. #  Power BI Visualization
Power BI is used to create interactive and informative visualizations that showcase the insights gained from the data analysis. The visualizations may include:

Bar charts and pie charts displaying sales by product category.
Time series charts illustrating sales trends.
Geographic maps showing the distribution of restaurant locations.
Dashboards summarizing key performance indicators (KPIs).


# Power BI Visualization

 ![Dashboard 1](https://github.com/ashrafkhan778/Pizza-Sales-Analysis/blob/main/Pizza%20Sales%20Report%20daskhboard.png)


 ![Dashboard 2](https://github.com/ashrafkhan778/Pizza-Sales-Analysis/blob/main/Pizza%20Sales%20Report%20daskhboard%202.png)

 5. # Insights and Recommendations
Based on the analysis and visualizations, actionable insights and recommendations are provided to the pizza restaurant chain. These insights can help in making informed decisions to improve sales, marketing strategies, and overall business performance.

# Dependencies
SQL database or data source
Power BI Desktop
