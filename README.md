# Business Insights 360

## Project Overview

AtliQ is a rapidly expanding hardware company that markets a diverse array of products to customers across various countries through multiple channels, including retail outlets, direct sales, and distributor networks, both online and in physical stores. To enhance its growth trajectory and enable data-driven decision-making, AtliQ requires a dedicated data analytics team.

- Live Dashboard - [Click to view](https://bit.ly/3YiRW0w)

## Technology Stack

- SQL
- Power BI
- Excel
- DAX Studio
- PowerPoint
- M Language
- DAX Language 

## Domain Knowledge

- Data analytics, data warehousing, data cataloging, OLTP, OLAP
- Star schema, snowflake schema
- FY - Fiscal Year
- YTD - Year to Date
- YTG - Year to Go
- Gross sales, pre-invoice deductions
- Net invoice sales, post-invoice deductions
- Net sales
- Manufacturing and freight costs
- COGS - Cost of Goods Sold
- Gross margin and gross margin percentage
- Gross margin per unit
- Net profit and net profit percentage
- Sales quantity and forecast quantity
- Net error, Absolute error, and forecast accuracy

## Data Importing to Power BI

In this project, we are utilizing a MySQL database to import datasets into Power BI. Access credentials for the database must be provided to facilitate this process.

### Database: gdb041
- **Dimension Tables:** These tables contain static data, including customer and product details.
  - `dim_customer`
  - `dim_market`
  - `dim_product`
  
- **Fact Tables:** These tables hold transactional data.
  - `fact_forecast_monthly`
  - `fact_sales_monthly`

### Database: gdb056
- **Cost-Related Tables:** These tables contain various cost metrics.
  - `freight_cost`
  - `gross_price`
  - `manufacturing_cost`
  - `Pre_invoice_deductions`
  - `Post_invoice_deductions`

- **Data Model (SnowFlake Schema)**
<img src=https://github.com/Teja-Reddy-kotha/Business-Insights-360/blob/main/Data%20Model%20(SnowFlake%20Schema).png>

## Project Workflow

1. **Planning and Scoping:** Initial project setup and definition of objectives.
2. **Project Charter:** A document outlining key details, including project objectives, stakeholder information, concerns and expectations, timeline, success criteria, and management of feature creep.
3. **Data Collection and Exploration:** Gathering data and creating a date table using Power Query (M Language).
4. **Project Management Soft Skills:** Engaging in proactive communication and asking pertinent questions to provide meaningful solutions within deadlines.
5. **Data Loading:** Importing data into Power BI and performing initial validation.
6. **Data Transformation:** Transforming data in Power Query.
7. **Data Modeling:** Establishing relationships and creating calculated columns.
8. **Measure Creation:** Developing measures with DAX language.
9. **View Development:** Building Finance, Sales, Market, and Supply Chain Views.
10. **Dashboard Design:** Crafting a user-friendly dashboard featuring page navigation buttons, dynamic titles based on filters, KPIs, and conditional formatting for visual values according to targets.
11. **Data Validation Setup:** Developing a user acceptance testing report.
12. **Stakeholder Feedback Implementation:** Adapting to feedback by enabling dynamic targets, employing what-if parameters and measures for slicers, using bookmarks for visual transitions, and creating tooltips to display trends, culminating in an Executive Dashboard.
13. **Solution Deployment:** Utilizing Power BI Service for report sharing.
14. **Automated Data Refresh:** Setting up data refresh capabilities through gateways.

## Project Outcomes

- **Finance View**: Developed comprehensive Profit and Loss (P&L) statements to track and analyze financial performance across multiple markets, products, and customer segments, supporting profitability insights.
  
  <img src=https://github.com/Teja-Reddy-kotha/Business-Insights-360/blob/main/Finance%20View.png>
- **Sales View**: Focused on building strong customer relationships by identifying top and bottom customers along with key metrics to drive business growth.
  
  <img src=https://github.com/Teja-Reddy-kotha/Business-Insights-360/blob/main/Sales%20View.png>
- **Marketing View**: Emphasized product promotion by running ads and executing marketing strategies, with insights on top and bottom products and key performance indicators.
  
  <img src=https://github.com/Teja-Reddy-kotha/Business-Insights-360/blob/main/Marketing%20View.png>
- **Supply Chain View**: Ensured efficient product production to prevent stockouts (OOS) and created KPIs such as forecast accuracy, net error, and absolute error to evaluate supply chain effectiveness.
  
  <img src=https://github.com/Teja-Reddy-kotha/Business-Insights-360/blob/main/Supply%20Chain%20View.png>
- **Executive View**: Consolidated key insights to support executive-level decision-making, providing valuable strategies for CEOs and managers.
  
  <img src=https://github.com/Teja-Reddy-kotha/Business-Insights-360/blob/main/Executive%20View.png>
