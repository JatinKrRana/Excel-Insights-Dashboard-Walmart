### **Excel Insights Into Walmart's Supply Chain Performance and Digital Trends**  
Project Link:- https://drive.google.com/drive/folders/1vRb_orNtJ9DT7G52GbS1d4VJfKtbarXP?usp=sharing

![walmart](https://github.com/user-attachments/assets/f1ab3a9a-d86e-41e6-9bf1-09ba1fdeb752)


#### **Background:**  

Walmart, a global retail giant, continuously seeks to enhance its supply chain efficiency and digital engagement to stay competitive. This case study, **"Excel Insights Into Walmart's Supply Chain Performance and Digital Trends,"** focuses on analyzing supply chain operations and online consumer behavior using two datasets: **SupplyChainDataset.csv** and **UserAccessLogs.csv**. The supply chain dataset provides insights into **sales, logistics, and delivery performance**, while the digital access logs capture **customer interactions and online preferences**.  

By examining these datasets, this study aims to uncover strategies for **streamlining logistics, optimizing inventory management, and enhancing digital marketing efforts**. Given the increasing importance of **efficient supply chain networks and a strong digital presence**, data-driven insights will be pivotal in driving operational excellence and improving customer engagement.  

#### **Objective:**  

The goal of this analysis is to leverage **advanced Excel techniques** to process, integrate, and analyze Walmart’s supply chain and digital access data. Key tasks include:  

- **Data Cleaning & Integration** – Handling missing values, transforming data types, and merging datasets for seamless analysis.  
- **KPI Development** – Defining key performance indicators (KPIs) such as **profit margins, delivery efficiency, product popularity, and online traffic patterns**.  
- **Interactive Dashboard Creation** – Building a **dynamic Excel dashboard** with visualizations to track **sales trends, order fulfillment efficiency, and customer engagement metrics**.  

This study aims to empower Walmart with **actionable insights** to refine its **supply chain strategy and digital outreach**, ensuring **better inventory planning, faster deliveries, and improved customer satisfaction**. The findings will also support strategic decisions in **product management, digital marketing, and customer relationship management**, reinforcing Walmart’s position as a leader in the retail industry.

### **Data Source:**

1. **Supply Chain Dataset:**

[DataCoSupplyChainDataset.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/4480950a-3a80-4276-9b10-2c483ae641c1/DataCoSupplyChainDataset.csv)

This dataset is designed to analyze aspects of the supply chain such as shipping efficiency, customer demographics, sales performance, and product popularity.

2.  **Access Logs Dataset**

[TokenizedAccessLogs.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/6ad8d24d-415f-4d13-8632-25f466a0fbe7/TokenizedAccessLogs.csv)

This dataset is for understanding user behavior on the website, the popularity of products, and the performance of different website sections.

### **Part 1: Excel Data Analysis: Manipulation, Formulas and Functions**

1. **Date Analysis**: The average shipping delay (difference between 'Days for shipping (real)' and 'Days for shipment (scheduled)') for each product category.

   ![Screenshot 2024-08-25 215317](https://github.com/user-attachments/assets/ae9e77a4-8a05-4973-be31-2ff80da919fc)

2. **Profit Margin Calculation**: The profit margin for each order, categorized as 'High', 'Medium', or 'Low'.

  ![Screenshot 2024-08-25 220442](https://github.com/user-attachments/assets/a9d59827-14c4-4f33-84d1-e184b83427bf)

3. **Customer Geographic Analysis**: The distribution of customers across different cities and countries.

![Screenshot 2024-08-25 220726](https://github.com/user-attachments/assets/25800e67-e21b-4395-930d-2df2cb4f236b)

4. **Sales Trend Analysis**: Monthly sales trends over the years and peak sales months.

![Screenshot 2024-08-25 220753](https://github.com/user-attachments/assets/85863dbf-23f5-48ab-8288-586d61b12e03)

5. **Top 5 products:** The top 5 products with the highest sales.

![Screenshot 2024-08-25 222523](https://github.com/user-attachments/assets/0fa7ecf9-a07a-4eb1-ade5-a8b187c71fca)

6. **Product Popularity Index**: Popularity index to rate product popularity based on sales volume and frequency.

![Screenshot 2024-08-25 223445](https://github.com/user-attachments/assets/59227b88-0d94-428b-82a2-843cc497d5cc)

7. **Dynamic Data Range for Sales Analysis**: Total sales for each category.

![Screenshot 2024-08-25 224006](https://github.com/user-attachments/assets/d80ead54-f0d4-47a2-9dff-ab0b3c45d3ba)

8. **Departmental Traffic Analysis**: Analyze which department's products are most frequently accessed using COUNTIF and SUMIF functions.

![Screenshot 2024-08-25 213944](https://github.com/user-attachments/assets/654d20c9-9179-4948-814b-bdfd03ae1fc2)

9. **Most Visited URLs**: The most frequently visited URLs.

![Screenshot 2024-08-25 221115](https://github.com/user-attachments/assets/b3b0fee8-2d40-4c9f-89c5-26aadcb44200)

10. **Product Interest vs. Sales Performance Analysis**: The frequency of product views from the Access Logs dataset with the sales data for the same products in the Supply Chain dataset.

![Screenshot 2024-08-25 221143](https://github.com/user-attachments/assets/ccf75bf4-a706-49f2-be29-3bb9b6b5f5ba)

11. **Customer Geographic Interest Analysis**: Match the customer cities from the Supply Chain dataset with IP addresses from the Access Logs dataset (approximate analysis due to the nature of IP geolocation). Analyze which cities show the most online engagement compared to actual sales.

![Screenshot 2024-08-25 221241](https://github.com/user-attachments/assets/a101cb4c-0468-4b04-b590-de35edd92449)

12. **Time Series Analysis of Product Interest and Sales**: Compare the monthly trends in product views from the Access Logs dataset with the monthly sales trends of those products in the Supply Chain dataset. Identify any lag or lead relationship between interest and sales.

![Screenshot 2024-08-25 221257](https://github.com/user-attachments/assets/5a58c826-0020-4870-8daa-7543dfe97237)

### **Part 2: Building an Excel Dashboard**

Leverage Excel's data visualization and interactive tools to create an insightful and dynamic dashboard. This dashboard should provide a clear and interactive overview of key performance indicators (KPIs), trends, and insights in the supply chain and web access areas. The goal is to develop a tool that facilitates data-driven decision-making and offers a comprehensive understanding of the underlying business processes.

![Screenshot 2024-08-24 144249](https://github.com/user-attachments/assets/5a499344-659e-42ef-b4e7-8b9957ccec62)
