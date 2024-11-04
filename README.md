# LITA-CAPSTONE-PROJECT

### Project Title 1: Sales Performance Analysis for a Retail Store
### Project Title 2: Customer Segmentation for a Subscription Service

[Project Overview](#project-overview)

[Methodology](#methodology)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)


### Project Overview:
1.	The objective of this project is to analyze the sales performance of a retail store and provide insights to improve business decisions. The analysis will focus on identifying trends and patterns between sales data and various factors such as product categories, regions, customer id, quantity sold and seasonal fluctuations to have insight on suitable performance to adopt
2.	This project aims to analyze customer performance metrics for a retail store, identifying trends, patterns, and insights to inform business decisions, improve customer satisfaction, and drive sales growth to make reasonable decision.

### Methodology
-	Spreadsheet software (Excel) [Download Here](https://www.microsoft.com)
1.	Data entry and storage
2.	 Data analysis and filtering
3.	Basic arithmetic operations (sum, average, count)
4.	Pivot tables and summaries

-	Structured Query Language (Sql)
1. Data retrieval and manipulation
2. Data definition and modification
3. Data control and access

-	Data visualization (Power BI)

1. Interactive dashboards and reports
2. Data analysis and visualization
3. Business performance monitoring
4. Data-driven decision-making

-	Portfolio (Github)
1. Source code management
2. Version control (Git)
3. Collaboration and teamwork
4. Open-source software development

### Data Cleaning and Preparations
In Data cleaning and preparations, I perform the following task;
1.	Data loading and inspection
2.	Converting from table to range
3.	Converting years to days
4.	Sorting
5.	Adding calculated column
6.	Data cleaning and formatting
### Exploratory Data Analysis
EDA involved the exploring of the Data to answer question such as;
-  What are the oversell sales by product, region and months?
-  Which product, region and months has more sales?
-  What quantity sold by each product and region?
-  What are names of the customer?
-  Which subscription has more revenue?
-  What’s subscription duration?

### Data Analysis
The basic lines of code or queries or Dax used during this analysis;

```SQL
Select top 1 Product,sum(sales) as "Highest Product" from [dbo].[SalesData] group by Product order by "Highest Product" desc
```
```SQL
Select (select sum(sales) *100 from [dbo].[SalesData] where region='North' ) /(select sum(sales) from [dbo].[SalesData]) as "% Contributed"
```
```SQL
Select customerName as "Sub More Than 12 Months" from [dbo].[CustomerData] where Duration>366
```
```Powerbi
Basic Revenue =SUMX(FILTER(CustomerData,CustomerData[SubscriptionType]="Basic"),CustomerData[Revenue])
```
  ### Data Visualization
        |Heading 1|Heading 2|Heading 3|
        |-------------|-------------|--------------|
        |Table 1|Table 2|Table 3|



