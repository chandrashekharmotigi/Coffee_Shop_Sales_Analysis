## **Coffee Shop Sales Dashboard Analysis**

### **Objective**
The primary objective of this Power BI dashboard is to deliver an in-depth analysis of a coffee shop’s sales performance. This project targets key aspects of sales, order volume, product category performance, and location-wise sales trends, enabling the management to recognize patterns, identify peak times, and strategize improvements.

### **Project Scope and Problem Definition**
The coffee shop aims to gain a better understanding of its sales dynamics to address specific challenges:
- Identifying overall sales patterns and fluctuations over time.
- Comparing sales between weekdays and weekends to spot any meaningful variations.
- Tracking sales contributions from various store locations and product categories.
- Recognizing high-performing products and understanding the impact of time (days and hours) on sales performance.

By analyzing these aspects, the goal is to pinpoint key sales drivers and develop actionable strategies for improvement.

### **Tools and Technologies Utilized**
- **Microsoft Excel**: Initial data cleaning, preliminary calculations, and transformations.
- **Power BI**: For dynamic visualization, data transformation, and detailed analysis.

### **Data Preparation and Transformation**

**Excel**
1. **Data Type Standardization**: Ensured that columns like sales amount, quantity, and order IDs were properly formatted as numeric values.
2. **Null Handling**: Replaced or filled missing values, using the median where necessary to maintain data integrity.
3. **Consistent Labels and Categories**: Ensured uniform naming for product categories and locations for clear categorization.
4. **Date Formatting**: Converted all dates into a consistent format to facilitate time-based analyses.

**Power BI**
1. **Data Modeling**: Created a date table and established a connection with the main sales data table for seamless time-based filtering and analysis.
2. **Data Transformation**: Used Power Query to clean and standardize data, including removing duplicates, filtering specific rows, and validating entries.
3. **Conditional Formatting**: Applied conditional formatting on visualizations to emphasize important metrics and emerging trends.

### **Visual Analytics and Key Features**

1. **Total Sales, Orders, and Quantity Analysis**:
   - **Cards and Line Charts**: Represented monthly totals for sales, orders, and quantities sold. Each card displays month-over-month variations, allowing quick comparisons.

2. **Sales Comparison by Weekdays vs. Weekends**:
   - **Pie Chart Analysis**: A pie chart splits sales data between weekdays and weekends, revealing behavioral differences in customer purchasing patterns.

3. **Store Location Performance**:
   - **Bar Chart for Location-Wise Sales**: Store sales are visualized across branches, allowing easy identification of top-performing locations. A month-over-month comparison metric shows changes in sales performance.

4. **Daily Sales Trends with Average Line**:
   - **Column Chart with Average Line**: Displays daily sales with a reference line for average sales, making it easy to identify days with unusually high or low performance.

5. **Product Category Sales Breakdown**:
   - **Bar Chart by Product Category**: Shows which product categories drive the highest sales, providing insights into popular products.

6. **Top 10 Best-Selling Products**:
   - **Bar Chart for Product Ranking**: Highlights the top 10 products by sales volume, assisting in pinpointing best-sellers.

7. **Sales Patterns by Days and Hours**:
   - **Matrix Heat Map**: Visualizes sales by hour and day, showing peak times and hours with higher sales activity. Tooltips on hover offer more context by displaying detailed metrics like total sales, orders, and quantity.

8. **Calendar Heat Map**:
   - **Day-Level Insights**: A heat map dynamically adjusts to the selected month, with darker shades representing higher daily sales volumes. Hovering over each day provides detailed insights.

### **Exploratory Data Analysis (EDA) Questions Addressed**
- **Total Sales Patterns**: What is the overall trend in total sales?
- **Order and Quantity Trends**: How do total orders and quantities sold vary month to month?
- **Weekday vs. Weekend Patterns**: Are there significant sales differences between weekdays and weekends?
- **Store Location Insights**: Which locations perform the best and contribute the most to sales?
- **Daily Sales Analysis**: Which days perform above or below average?
- **Product Category and Top Product Insights**: Which categories and products generate the most revenue?
- **Hourly Sales Trends**: What are the peak sales times by day and hour?

### **Visualizations and Dashboard Design**

- **Cards and Line Charts**: For an overview of total sales, orders, and quantities across time.
- **Pie Chart**: Highlights weekday vs. weekend sales distributions.
- **Bar and Column Charts**: Showcase sales by store location and product category.
- **Matrix Chart**: For a detailed view of hourly sales patterns.
- **Calendar Map**: A dynamic heat map for granular daily sales insights with hover tooltips.

### **Project Insights and Outcomes**
The Coffee Shop Sales Analysis dashboard offers a powerful tool for decision-making. Management can:
- Understand sales behavior by time and location.
- Identify top products and sales-contributing categories.
- Use insights on peak sales times to align staffing and promotional activities.
- Recognize underperforming locations or products and take corrective action.

This analysis is integral for strategic planning, allowing for more data-driven decisions that can enhance the coffee shop’s market presence and profitability.
