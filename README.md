# MY-LITA-PROJECT-The-Capstone-Dataset.
This is where i am going to document the project given to me by TheIncubatorHub through LadiesInTech Africa (LITA). Follow me along through the journey and feel free to comment.
## Project Title: THE CAPSTONE DATASET
The capstone dataset is a dataset given as a project to work on as my project to becoming a Data Analyst. This project contains two dataset:
- Sales Performance Analysis for a Retail Store
- Customer Segmentation for a Subscription Service
  
### Sales Performance Analysis

- Analyze sales data to identify trends and insights
- Identify top-selling products, regional sales performance, and monthly sales trends
- Provide recommendations for sales growth and improvement

### Customer Segmentation

- Analyze customer data to identify segments and trends
- Identify customer demographics, subscription patterns, and cancellation trends
- Provide recommendations for customer retention and growth

## Detailed Tool Usage

-	Excel:
    1. Data cleaning and preprocessing
    2. Pivot tables and charts for data visualization
    3. Formulas and calculations for data analysis
-	SQL:
    1. Data querying and filtering
    2. Joining and merging datasets
    3. Aggregate functions for data analysis
-	Power BI:
    1. Data visualization and dashboard creation
    2. Interactive reports and slicers
    3. Publishing and sharing dashboards

## QUESTIONS: Sales Performance Analysis
 ### Excel:
- Perform an initial exploration of the sales data. Use pivot tables to summarize total sales by product, region, and month.
 ![Screenshot (5)](https://github.com/user-attachments/assets/85501829-ae36-45c4-8da4-0302dc7fa3b3)
- The Image above shows a cleaned dataset after removing duplicate and calculating the Sales.
 <img width="976" alt="Q1 Sales" src="https://github.com/user-attachments/assets/d4674655-8827-46f3-aacb-ddf2600c731e">
The image above is the total sales by product, region and month using pivot table.
- Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.
 <img width="950" alt="Q2 Sales" src="https://github.com/user-attachments/assets/2165865c-e3b3-4a54-8319-35fb06f31b50">
The image above is the average sales per product and total revenue by region using excel functions. To get this i first unique out products and region respectively and then used the *sumif* function.
- Create any other interesting report
  <img width="508" alt="SALES EXCEL DASHBOARD COR" src="https://github.com/user-attachments/assets/bd0dff68-10c9-4e48-aa19-7b94eb037fc6">


  ### SQL:
Hint – You need to load the dataset into your SQL Server environment to write and validate your queries.
Write queries to extract key insights based on the following questions. 
- retrieve the total sales for each product category.
  ![Q1 SQL sales](https://github.com/user-attachments/assets/361887a9-02db-44a7-a747-4f50711357a9)
- find the number of sales transactions in each region.
  ![Q2 SQL sales](https://github.com/user-attachments/assets/d7b0d9b0-3972-47ae-ad41-bed33a233236)
- find the highest-selling product by total sales value.
  ![Q3 SQL sales](https://github.com/user-attachments/assets/ea670cb1-9ab8-47e5-b02e-39158652b78f)
- calculate total revenue per product.
  ![Q4 SQL sales](https://github.com/user-attachments/assets/16ed6535-a0c5-4010-9229-4050a97d48a6)
- calculate monthly sales totals for the current year.
- find the top 5 customers by total purchase amount.
  ![Q6 SQL sales](https://github.com/user-attachments/assets/f3250be6-a601-4b69-867d-3234334d933f)
- calculate the percentage of total sales contributed by each region.
  ![Q7 SQL sales](https://github.com/user-attachments/assets/f43249e9-01b4-40ac-834b-fa1e195407ce)
- identify products with no sales in the last quarter.
  <img width="968" alt="sales sql 8" src="https://github.com/user-attachments/assets/ae86d0cf-a3b8-41d9-8013-ab1ff4199a92">


  ### Power BI:
- Create a dashboard that visualizes the insights found in Excel and SQL. The dashboard should include a sales overview, top-performing products, and regional breakdowns
<img width="719" alt="BI Sales" src="https://github.com/user-attachments/assets/99f25786-795b-4b81-8911-b2fd2113fd34">

### CONCLUSION
From the above dashboard we can draw a conclusion that:
- The regionwith the higher sales is the *SOUTH*, While the region with the lowest sales is the *WEST*, We have to carry out a survey to know why sales is poor in the westand then come up with a solution to maximize sales there.
- Also the product with the higher sales is the *SHOE* while *JACKET and SOCKS* is least even during harmattan season, which is odd. We have to carry out a survey to know why these products are performing poorly. So we might end up doing a popup sale of buy 1 get 1 free.

  
  ## QUESTIONS: Customer Segmentation

  ### Excel:
- Analyze customer data using pivot tables to find subscription patterns.
  <img width="963" alt="c;;eaned Customer" src="https://github.com/user-attachments/assets/f0ed14c0-704d-4e68-aedb-3f56d783303a">
- The Image above shows a cleaned dataset after removing duplicate and calculating the Sales.
  <img width="973" alt="Q1 Customer" src="https://github.com/user-attachments/assets/5ed03caa-d601-44cd-a651-3d50b73897b7">
-The image above shows the subscription patterns.
- Calculate the average subscription duration and identify the most popular subscription types.
- Create any other interesting reports.
  <img width="548" alt="CUSTOMER EXCEL DASHBOARD COR" src="https://github.com/user-attachments/assets/828bfdc6-8892-4409-9bef-260d99ae45dc">



  ### SQL:
Hint – You need to load the dataset into your SQL Server environment to write and validate your queries. Write queries to extract key insights based on the following questions. 
- retrieve the total number of customers from each region.
  <img width="964" alt="Q1 SQL Customer" src="https://github.com/user-attachments/assets/df24836a-8818-41af-9576-7e8163bd5dad">
- find the most popular subscription type by the number of customers.
  <img width="954" alt="Q2 SQL customer" src="https://github.com/user-attachments/assets/65d023c5-015d-4530-b5e5-5b7b9550bc3b">
- find customers who canceled their subscription within 6 months.
  <img width="955" alt="Q3 SQL Customer" src="https://github.com/user-attachments/assets/adb11f39-9efe-4098-a792-5033e87f8f35">
- calculate the average subscription duration for all customers.
  <img width="953" alt="Q4 SQL Customer" src="https://github.com/user-attachments/assets/30cec909-fa47-4d86-84a8-5745ddbff1c6">
- find customers with subscriptions longer than 12 months.
  <img width="959" alt="Q5 SQL Customer" src="https://github.com/user-attachments/assets/cfd49ba1-0e11-4056-bf2f-6c599d784dfb">
- calculate total revenue by subscription type.
  <img width="955" alt="Q6 SQL Customer" src="https://github.com/user-attachments/assets/46e9c081-45e3-4ef4-8446-ae79ee4b27fb">
- find the top 3 regions by subscription cancellations.
  <img width="953" alt="Q7 SQL Customer" src="https://github.com/user-attachments/assets/7592f650-89bd-4900-9c8f-62c57201a2e7">
- find the total number of active and canceled subscriptions.
  <img width="964" alt="Q8 SQL Customer" src="https://github.com/user-attachments/assets/1854f255-ab2d-407e-84f6-e70e792c7ee8">


  ### Power BI:
- Build a Power BI dashboard that visualizes key customer segments, cancellations, and subscription trends. Include slicers for interactive analysis.

### CONCLUSION
From the above dashboard diagram we camn draw a conclusion that:
- Each of the 4 regions only purchased one each of the subscription type, we need to carry out survey in all of the regions to know why this is happening. 
