# Amazon Products Sales Analysis| Power BI Dashboard 

## Project Objective
To design an interactive Power BI dashboard that analyzes Amazon sales and review data, with the goal of providing actionable insights into revenue performance, product category trends, and customer feedback. The objective is to support data-driven decisions in inventory planning, pricing strategy, and marketing by visualizing key metrics such as YTD Sales, product movement, and customer reviews.

## Dataset Used
- <a href="https://github.com/Anbu0007/Data-Analysis-Dashboard/blob/main/Amazon_Combined_Data.xlsx">Dataset</a>

## Problem Statement 
### KPI's Requirement 
- YTD Sales: Monitor year-to-date sales to gauge the overall revenue performance over time.
- QTD Sales: Track quarterly sales figures to identify sales trends and fluctuations.
- YTD Products Sold: Analyse the total number of products sold throughout the year to understand product movement.
- YTD Reviews: Keep tabs on year-to-date product reviews to assess customer feedback and satisfaction.

### Charts Requirements
- Sales by Month (Line Chart): Visualize sales trends over time on a monthly basis to identify seasonal patterns and growth trends.
- Sales by Week (Column Chart): Display sales data on a weekly basis to pinpoint shorter-term fluctuations and performance insights.
- Sales by Product Category (Text/Heat Map): Utilize a text or heat map visualization to provide a high-level overview of sales across different product categories.
- Top 5 Products by YTD Sales (Bar Chart): Highlight the top-performing products based on year-to-date sales to focus on key revenue generators.
- Top 5 Products by YTD Reviews (Bar Chart): Identify the top-rated products by year-to-date reviews to understand customer preferences.

- Dashboard Interaction <a href="https://github.com/Anbu0007/Data-Analysis-Dashboard/blob/main/IMG-20250701-WA0014.jpg">View Dashboard</a>

## Process
- Imported and cleaned 89K+ rows of Amazon sales data in Power BI, ensuring data consistency and structure.
- Transformed data using Power Query and built relationships across product, sales, and date tables.
- Created KPIs like YTD Sales, QTD Sales, and YTD Reviews using DAX and time-intelligence functions.
- Designed interactive visuals including monthly/weekly trends, category heat maps, and top product charts.
- Optimized performance with a star schema and slicers, enabling smooth filtering across large datasets.

## Dashboard 
![Screenshot 2025-07-01 160138](https://github.com/user-attachments/assets/3b87d80b-938e-466f-ba40-29eadbd550f2)

## Project Insights
- Men’s Shoes dominate sales with 43% of total YTD revenue, indicating strong demand.
- Sales peaks in Q4 (especially in December), suggesting the importance of seasonal promotions.
- Customer reviews (19.42M) show strong engagement, especially for storage devices like SanDisk, highlighting areas of high customer interest.
- A steady increase in weekly sales toward the end of the year implies opportunity for inventory planning ahead of festive seasons.

## Conclusion
This project successfully converted raw Amazon data into a dynamic Power BI dashboard that enables real-time tracking of sales and customer sentiment. By identifying top-performing categories and products, the dashboard supports strategic business decisions in marketing, inventory, and pricing. With clear visualizations and KPI monitoring, the solution enhances business visibility and enables data-backed growth strategies.
