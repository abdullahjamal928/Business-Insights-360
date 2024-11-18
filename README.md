# AtliQ Business Insights 360

## Project Overview

**AltiQ Hardware** is a rapidly growing company that specializes in selling computers and accessories across multiple channels, including retailers, direct sales, and distributors. However, despite its growth, the company encountered unexpected losses after opening a store in the USA. These issues were first noticed through surveys, intuition, and basic Excel analysis. With competitors having robust analytics teams, AltiQ realised the urgent need to enhance its data capabilities to stay competitive.

To tackle this, AltiQ decided to implement **Power BI** for better analytics. The goal of this project was to provide stakeholders with valuable insights into finance, sales, marketing, and supply chain, helping them make well-informed decisions.

This project was completed as part of the **Codebasics Power BI Course**, where I focused on building an interactive dashboard to address the company's business needs.

## Report Links
- [Power BI Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYWM2MDVmOTgtZDA2Mi00NzY3LTg5ODYtZGMxOTFkOGIxZjNiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).

## Datasets

Before jumping into the analysis, it’s important to understand the datasets. We worked with two main types of tables:
**Dimension table**: Static data like customer and product details.
**Fact table**: Transaction data.

gdb041:

- dim_customer
- dim_market
- dim_product
- fact_forecast_monthly: Monthly forecast data that helps predict customer demand, improving customer satisfaction and reducing storage costs in warehouses.
- fact_sales_monthly: Monthly sales data, showing actual sales figures, unlike the forecast table.

gdb056:

- freight_cost
- gross_price
- manufacturing_cost
- Pre_invoice_dedutions
- Post_invoice_deductions

## Data Importing and Data Modeling

The data was imported from MySQL into Power BI, where it was cleaned and transformed. **Data modeling** is a crucial step in analytics because it builds the foundation for your reports. Without a good model, your analysis can go off-track. We used the **Snowflake schema** for structuring the data, ensuring that all data points were connected and easy to analyse.

### Data Model Overview:

If you break down the whole work of a data analyst then you will come up with 4 steps of work

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

See you can't skip the 3rd step if you want to reach the last step (analysis part), Data modeling is essential because it lays the foundation for reports. All visuals are built upon the data model, and poor modeling can affect report performance.

In this project, we used the the **Snowflake schema** data modeling method.

![Data Model](https://github.com/user-attachments/assets/5243f1ec-7230-4753-8b2b-8f1e28b7837e)


## Power BI Dashboard Overview

The dashboard is designed to offer stakeholders easy access to key metrics. It consists of six pages:

1. **Home Page**: A simple landing page with buttons to navigate to different sections.
![#1](https://github.com/user-attachments/assets/6d158f88-a269-451c-901e-a4740d2018ef)

2. **Finance Page**: Includes Profit & Loss statements, Top Products/Customers by Net Sales, and more.
![#2](https://github.com/user-attachments/assets/e5136209-aad3-4c9d-b00c-791cfb15b16a)

3. **Sales Page**: Displays customer performance by Net Sales, Gross Margin, and Gross Margin %, among other metrics.
![#3](https://github.com/user-attachments/assets/045f6ab4-c6df-4fc4-83ff-0c757a5dbc4d)

4. **Marketing Page**: Focuses on segment performance, Gross Margin%, and Net Profit%.
![#4](https://github.com/user-attachments/assets/7377846d-8850-47aa-9c39-44fd1dc6f3cf)

5. **Supply Chain Page**: Helps optimize inventory and supplier relationships by displaying metrics like Forecast Accuracy and Net Error.
![#5](https://github.com/user-attachments/assets/3b074c6a-49a6-4d6b-bdd2-0a180d9d60bd)

6. **Executive Page**: A high-level overview with key figures like Net Sales, Gross Margin%, Net Profit%, and more, aimed at top management.
![#6](https://github.com/user-attachments/assets/7991832a-cac7-40da-89e0-b611e61ccd6c)


## Skills Learned

During this project and the **Codebasics Bootcamp**, I gained valuable skills:
- Power BI basics and advanced techniques **(calculated columns, DAX measures, data modeling, data cleaning)**.
- Creating dynamic reports with features like **Bookmarks, Conditional Formatting, Custom Tooltips, and Dynamic Titles, and many more**.

## Tools Used
- **SQL**: For querying and extracting data.
- **Power BI Desktop**: For building the dashboard and reports.
- **DAX**: For creating powerful calculated columns and measures.
- **DAX Studio**: To optimise the Power BI file size and improve report performance.
- **Project Charter file**: Formal document that outlines the key details of a project, including its scope, objectives, and stakeholders

## Business Terms Learned
- Key business metrics such as **Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.**

## Conclusion

This project enables AltiQ to make data-driven decisions by providing comprehensive insights into its business performance. The Power BI dashboard serves as a tool to not only answer critical business questions but also guide the company towards more profitable, informed choices.

This journey has been an exciting blend of learning and practical application, and I’m excited to see how data can truly empower businesses to perform at their best.
