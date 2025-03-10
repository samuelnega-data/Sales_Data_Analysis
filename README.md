# Sales Data Analysis Project

## Overview
I performed a thorough analysis of an item sales dataset that I obtained from Kaggle. This process involved cleaning, analyzing and visualizing the data using Excel.

## Location of Dataset
[https://www.kaggle.com/datasets/aliazimieco/rfm-dataset?select=arpand_ecommerce_dataset.csv](https://www.kaggle.com/datasets/joelearns/sales-data-analyst?select=sales_data_analysis.xlsx)

## Understanding the Dataset 
- Order Number: A unique identifier assigned to each order.
- Date: The date when the order was placed.
- Sales Rep: The salesperson responsible for the order.
- Region: The geographical area where the sale was made.
- Customer ID: A unique identifier for the customer.
- Company Name: The name of the company placing the order.
- Company Rep: The representative of the company handling the order.
- Model: The product model ordered by the customer.
- Color: The color of the product ordered.
- Item Code: A unique code assigned to the product.
- Quantity: The number of units ordered.
- Price Per Unit: The cost of one unit of the product.
- Total Sales: The total revenue generated from the order (Quantity × Price Per Unit).

## Cleaning the Dataset 
- Fixing Sales reps name:
  - We couldn't use a VLOOKUP in this case since each region has two designated sales reps. Instead, we manually filtered the data by region and name, corrected the names, and assigned them to the appropriate rows and columns.
- Cleaning the Mode, Color, Item, Region and Item Code
  - I used the PROPER and TRIM functions on all the designated rows to ensure the data is formatted correctly. This way, when we create our pivot tables, we won’t encounter any errors due to inconsistent or improperly formatted text.
- Cleaning Numerical Values:
  - I ensured that each column was formatted with the appropriate numerical value, specifically for the Date and Total Sales columns.
 
 ## Before and After Dataset Cleaning
![Screenshot 2025-03-10 140419](https://github.com/user-attachments/assets/8c2f0113-0dc5-404c-ac0d-e8a9c0449785)
![Screenshot 2025-03-10 140353](https://github.com/user-attachments/assets/92de18d0-c0fb-49ef-8aa4-fb4a10b6d095)

## Pivot Tables 
![Screenshot 2025-03-10 140639](https://github.com/user-attachments/assets/40a83442-a473-4c94-a5c5-a53989d642d0)

## Sales Dashboard
![Screenshot 2025-03-10 134710](https://github.com/user-attachments/assets/176d6c8a-8beb-4197-8345-8c07f70a7e2d)
