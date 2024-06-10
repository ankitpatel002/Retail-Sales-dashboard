# Retail-Sales-dashboard

I've recently developed an advanced retail sales dashboard designed to provide comprehensive insights into key performance indicators (KPIs). The dashboard includes five essential KPIs: total sales, total profit, total sales year-to-date (YTD), total sales from the previous year, and total quantity sold. To visualize data effectively, I've incorporated various charts, including a waterfall chart showcasing quantity sold by product category, and two donut charts illustrating profit by quarter and total sales by gender. Additionally, four stacked column charts display sales by product category, profit by age group, sales by age group, and sales by day. To further analyze trends, there's a line chart tracking profit by day and a stacked bar chart detailing sales by month.

Key Features
DAX Calculations:

Total Sales: SUM(Sales[Amount])
Total Profit: SUM(Sales[Profit])
Total Sales YTD: TOTALYTD(SUM(Sales[Amount]), Calendar[Date])
Total Sales from Previous Year: CALCULATE(SUM(Sales[Amount]), SAMEPERIODLASTYEAR(Calendar[Date]))
Total Quantity Sold: SUM(Sales[Quantity])
These DAX calculations enable dynamic and real-time data analysis, ensuring that the KPIs and visualizations are always up-to-date.

Interactive Features:

Drill-Down Capabilities: Users can click on specific data points to drill down into more detailed views, such as examining sales by individual product or specific time periods.
Slicers and Filters: Various slicers and filters are incorporated to allow users to segment the data by different dimensions like product category, age group, gender, and time period.
Hover Tooltips: Detailed information is provided on hover, offering additional context and insights without cluttering the visualizations.
Visualization Insights
Waterfall Chart: Showcases the contribution of each product category to the total quantity sold, highlighting which categories are driving sales.
Donut Charts: Provide a clear view of profit distribution by quarter and total sales by gender, helping to identify seasonal trends and gender-based purchasing behaviors.
Stacked Column Charts: Offer a breakdown of sales and profit by various demographics and time periods, facilitating targeted marketing and inventory decisions.
Line Chart: Tracks daily profit trends, enabling businesses to quickly identify and respond to peaks and troughs in profitability.
Stacked Bar Chart: Details monthly sales, assisting in recognizing long-term trends and seasonality.
Practical Applications
This dashboard empowers retail businesses to make data-driven decisions and optimize their strategies for enhanced performance. For example, a retailer can identify underperforming product categories and implement targeted promotions or adjust inventory levels accordingly. The age and gender insights can inform personalized marketing campaigns, improving customer engagement and sales.
