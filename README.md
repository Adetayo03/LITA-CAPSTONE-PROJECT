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
  
![Chart](https://github.com/user-attachments/assets/59cbb20e-45bd-4125-b03c-ab65d5e6aa9d)



![CustReport Excel 1](https://github.com/user-attachments/assets/1e9bc43d-5772-41f1-96cc-8e504e48d020)


![CustReport Excel 2](https://github.com/user-attachments/assets/d79b7cb8-1490-44e1-aac9-47d9e906de03)

  
      
![custReport powerbi](https://github.com/user-attachments/assets/246b6a6b-6294-4dd3-9e59-8a4a8f1726c7)

        
![CustReport sql1](https://github.com/user-attachments/assets/721fb7b8-dd7d-4e77-8349-7fbde986f360)

        
![CustReport sql2](https://github.com/user-attachments/assets/7571e62f-2a79-4ba4-ba0b-b093f9fca1db)


![CustReport sql3](https://github.com/user-attachments/assets/3c083520-cd65-4065-a2a6-ac47fa60facb)



![SalesReport Excel](https://github.com/user-attachments/assets/e9857e8a-5bb1-4365-9a22-881c85495868)


![SalesReport Excel2](https://github.com/user-attachments/assets/5abf089f-18b1-4754-8e1b-2080e23b2037)


![SalesReport sql1](https://github.com/user-attachments/assets/aeb3ef62-6573-448a-a5a2-1936288c4730)



![SalesReport sql2](https://github.com/user-attachments/assets/9b82fd07-3290-4507-8d30-225c9b37629e)



 ![SalesReportsql3](https://github.com/user-attachments/assets/ae6f5581-e251-404a-8c5f-2bd69e3bb0f5)

    
 ![SalesReport Excel2](https://github.com/user-attachments/assets/887182b7-83ae-42af-a330-c91993a474c8)


![SalesReport powerbi](https://github.com/user-attachments/assets/7f3e6755-2f51-46a7-bd1b-2236ba970df4)

        
  💻📚🖋️
  💰💲🤑
  😆🕹️🗺️
  💃💃💃
        



