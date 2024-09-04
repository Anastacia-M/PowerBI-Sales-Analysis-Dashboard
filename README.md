# Sales Analysis Dashboard

## Project Overview
This data analysis project aims to provide an in-depth understanding of sales performance across different regions and sales representatives for the years 2021 and 2022. The main objective was to create an interactive Power BI dashboard that allows users to explore sales data, track key metrics such as total sales, average unit costs, and maximum unit costs, and identify trends and patterns that can inform business decisions.

## Data Sources
The primary dataset used for this analysis is the [Sales_data_2021_2022.xlsx](https://github.com/user-attachments/files/16858918/Sales_data_2021_2022.xlsx) file, which contains detailed information on sales transactions, including order dates, regions, representatives, items, and unit costs.

## Tools
**Power BI:** Utilized for data analysis, report creation, and interactive visualizations.

## Data Cleaning and Preparation
The data cleaning process involved:
Importing the sales data from the "Sales_data_14.xls" file into Power BI.
Creating a calculated table to generate a calendar range from January 1, 2021, to December 31, 2022.
Ensuring that all data fields, such as order dates, regions, and representatives, were properly formatted and free from errors.
Preparing and organizing the data to enable seamless filtering and analysis within the dashboard.

## Exploratory Data Analysis
To provide users with the ability to explore the sales data effectively, the dashboard was designed with the following key questions in mind:

1) **Sales Performance by Region:** How do total sales compare across different regions? From the chart, we can observe that the **Central region** dominates with 56.75% of total sales, followed by the **East region** with 30.58%. The **West region** contributes the least, making up only 12.67% of total sales. This highlights the Central region as the key driver of sales, while the East region holds a strong middle position. <br />
2) **Sales Representative Insights:** Which sales representatives are performing the best, and how are the sales figures distributed by item sold? The top three performing representatives are **Kivell** from the Central region, **Parent** from the East region, and **Jardine** from the Central region. Kivell and Parent have similar sales figures. Almost half of Kivell's sales come from Pen Sets, whereas over half of Parent's and Jardine's sales come from Binders. <br />
3) **Item-Level Analysis:** What item generates the most sales? **Binders** lead by a significant margin in terms of sales volume, making them the top-selling item across all categories. <br />
3) **Cost Analysis:** How do maximum unit costs impact overall sales performance? Despite having the second-lowest maximum unit cost, **Binders** generate the highest sales. Conversely, **Desks** have the highest maximum cost among all items but contribute the least to overall sales. This suggests that lower-priced items tend to drive higher sales volume.

These questions are intended to guide users as they interact with the dashboard, allowing them to filter and drill down into the data based on their specific interests.

## Results and Findings
The final Power BI dashboard includes several interactive visuals:

**Total Sales by Region:** A pie chart visual that displays total sales distributed across different regions. <br />
**Sales Representative Performance:** A line and stacked column chart that shows total sales and average sales per representative, with the ability to filter by region and representative.<br />
**Item-Level Sales and Cost Analysis:** A line and clustered column chart that compares total sales with maximum unit costs for each item.

This interactive dashboard enables users to gain valuable insights into sales trends, identify top-performing regions and representatives, and understand the impact of unit costs on overall sales. By leveraging these insights, users can make informed decisions to optimize sales strategies and improve performance across different segments.

You can review the final dashboard by referring to the provided screenshot and interacting with the Power BI file in the repository as needed.

![Sales Analysis Dashboard](https://github.com/user-attachments/assets/ef1620c3-850c-4520-8f12-38ef27b60992)
