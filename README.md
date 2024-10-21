                                Introduction to Vehicle Sales Performance Insights
                                

This project analyzes a vehicle sales and orders dataset to provide business insights using Power BI’s data visualization tools. The dataset includes order numbers, product details, pricing, sales data, customer information, and shipping across regions. The project will identify sales trends, top-performing products, and customer behaviors, while also highlighting inefficiencies in order processing and delivery. By comparing actual and forecasted sales, it aims to improve sales forecasting accuracy, helping drive better decision-making and performance optimization.

                                Objective
                                
The main objectives of the project are-
* Sales Analysis: Analyze sales data based on various factors such as country, product line, deal size, and year.
* Order Performance: Understand the relationship between sales, and estimated sales (Esales).
* Product Insights: Identify which product lines contribute most to the overall sales.
* Geographical Analysis: Examine sales distribution across different countries and territories (EMEA).
* Business Decision Support: Provide insights that can aid business decisions regarding product focus, pricing strategies, and market expansion.

                                 Tasks
The project tasks include-

Data Loading and Preparation:
* Import the dataset into Power BI and review data integrity.
* Ensure that all columns are properly formatted (e.g., dates are formatted correctly, numerical fields such as "Sales" and "Unit Price" are usable for analysis)

Data Cleaning:

* Handle missing or incomplete data (e.g., missing values in the "State" field where it says "No information").
* Filter out irrelevant data and remove duplicates if any.
* Change data type, rename columns, replace values, reorder columns, sort rows

Data Transformation:

* Create calculated columns such as total sales per year or profit if needed.
* Format "Order Date" and "Delivery Date" fields to proper date format for date-based analysis.

Visualizations: Create charts for key insights--

* Sales by Country: A bar chart to display the Count of sales orders per country.
* Sales vs Esales: A comparison of actual sales and estimated sales
* For each order use a clustered bar chart.
* Deal Size: A pie chart to show the sum of order numbers by deal size.
* Product Line Analysis: A stacked column chart to show the contribution of each product line to the Count of sales orders.
* Sales Over Time: A line chart showing sales trends over the years.
* Order Status Breakdown: A stacked column chart to visualize the different territories performing (sales, territories, etc.).

                                   Dashboard  & Report Creation
  <img width="614" alt="Dashboard" src="https://github.com/user-attachments/assets/f3383088-e0a9-45c7-bba4-1f31526438b3">

This Power BI report creates an interactive dashboard that combines all visualizations into a single page, allowing users to explore data using filters and slicers, such as by year or region. Clicking on a company reveals detailed information about its location, sales, and products. The dashboard provides insights into sales trends, product performance, customer behaviors, and delivery processes, enabling users to drill down into specific details and make informed decisions with an intuitive and seamless experience.

Company-Level Details Display:

* Click on Any Company: By selecting a company from the dataset (using a slicer or clickable visual element such as a table or chart), Power BI will automatically display complete details about that company.
* Location: Country, state, city, territory, and full address (e.g., "C/Moralzarzal/86, Madrid, Spain").
* Owner Name: First and last name of the owner (e.g., "Diego Freyre").
* Phone Number: Contact information for the company.
* Postal Code: ZIP code of the company’s location.

Order and Delivery Tracking:

* Order Date & Delivery Date: Power BI will show when a vehicle was ordered and when it was delivered for each specific company, allowing you to track the efficiency of orders and shipments.
* Order and Delivery Timeline: A visual timeline could be included to show how long the delivery process takes for each company.

Sales and Pricing Information:

* Total Sales and Estimated Sales (Esales): You can see the exact sales figures alongside estimated sales for that company. This helps in understanding if actual sales match or deviate from forecasts.
* Unit Price: The price per unit sold.
* Retail Price: The listed retail price of the product, allows you to compare it to the unit price to see if there are any discounts or price markups.

Product and Deal Information:

* Product Details: You can view the products purchased from the company:
* Most Purchased Product: Using a pie chart or bar chart, you can see which product has the highest number of sales or sales value.
* Product Line: Whether the company is dealing in "Classic Cars" or any other product category.
* Deal Size: Indicate whether the deal was classified as "Medium" or any other category (small, large).

Location Visualization:

* Map Integration: You can integrate Power BI's map visualization feature to automatically display the location of the selected company. When you click on a company, the location is shown on a map based on its city, state, and country. This helps in quickly visualizing where the company is located in the world.

Filtering by Products or Territories:

* You can filter the report by specific product lines (e.g., "Classic Cars") or territories (e.g., EMEA), which will automatically update all the related visuals like sales, order dates, delivery timelines, and product information.

                                       Outcomes

The outcomes of the project include:

* Comprehensive Sales Insights: Visualized sales trends across countries, product lines, and years, enabling stakeholders to see which regions and products are performing well.
* Performance Comparison: A clear comparison between sales and estimated sales (Esales), helps the company adjust forecasting models and pricing strategies.
* Delivery Efficiency: Insights into the delivery timelines by comparing order and delivery dates to help the logistics team improve delivery efficiency.
* Customer Behavior: An analysis of customer purchasing patterns across different regions and product lines.

                                      Challenges
  
Some challenges encountered during the project:

* Missing Data: Certain columns like "State" had missing information. The dataset had "No Information" in many state fields, which required thoughtful handling without affecting analysis accuracy.
* Date Format Issues: "Order Date" and "Delivery Date" were initially in non-standard formats, requiring transformation into a proper date format for time-series analysis.
* Data Consistency: Ensuring consistency in data types, particularly for numerical columns such as "Unit Price", "Sales", and "Esales".

                                     Final Report
  <img width="605" alt="Report" src="https://github.com/user-attachments/assets/888ce21e-6a24-4433-9cb0-ae520f69615f">

The final report consists of:

* Sales by Country
* Sales vs Esales
* Product Line Analysis
* Order Status Overview
* Sales by year
* Countries with the highest vehicle sales
* Count of sales orders by product line
* How closely Esales match the actual sales
* Focus on countries or regions with the highest sales potential for future marketing strategies.
* Improve delivery logistics to reduce delays.
* Review pricing strategies for underperforming product lines

                                      Conclusion
  
This interactive report allows stakeholders to:

* Access detailed company information in one click.
* Visualize sales data, product purchases, and delivery performance in a structured format.
* Filter data dynamically to compare different companies, products, and territories.
* Track order-to-delivery timelines to assess efficiency. This comprehensive view will help make strategic decisions on marketing, product development, and logistics management.








.



