# retail_store_sales_analysis
Data cleaning and exploratory analysis of a messy retail sales dataset, covering sales trends, category performance, and customer behavior.

## Project Overview
This project explores a real-world, intentionally messy retail sales dataset containing over twelve thousand transactions, selected specifically to practice data cleaning skills on unstructured, incomplete data rather than a pre-cleaned teaching dataset.

## Exploratory Data Analysis
Rather than starting from preset questions, this project used open-ended exploratory data analysis to uncover insights in three areas: sales trends over time, category performance, and customer purchasing behavior.

## Data Cleaning
The dataset contained missing values across five columns. Rows with no way to recover missing Item, Price Per Unit, Quantity, and Total Spent together were labeled "Unknown" for Item, while numeric fields were left blank and excluded from calculations. Price Per Unit was recovered where possible using Total Spent divided by Quantity. Discount Applied blanks were labeled "Unknown" rather than assumed False, since missing data doesn't necessarily indicate no discount was given. Original columns were preserved alongside cleaned versions throughout for transparency.

## Key Findings 
Friday was the strongest sales day and Monday the weakest. January was the highest-performing month, though it also carried the highest count of missing Total Spent values, a caveat worth noting. Butchers led both in total and average spend per transaction, with Milk Products the weakest category. Customer_024 had the highest lifetime value while Customer_005 made the most frequent purchases, showing that frequency and spend don't always align in the same customer. Cash was the most used payment method, credit card the least.

## Project Files
The full analysis, including cleaning formulas, pivot tables, and charts, is available in the linked workbook below. The complete written findings and recommendations are available in the Key Insights document.

Key Insights File: https://github.com/Thelma-Kepe/retail_store_sales_analysis/blob/main/Retail%20store%20sales%20Key%20Insights.docx
Excel Workbook: https://github.com/Thelma-Kepe/retail_store_sales_analysis/blob/main/retail_store_sales.xlsx

## Dashboard
![Dashboard Preview](https://private-user-images.githubusercontent.com/123815037/665838983-345b9f97-3029-42ed-88d6-44d6215b494a.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTEyMTU0ODEsIm5iZiI6MTc5MTIxNTE4MSwicGF0aCI6Ii8xMjM4MTUwMzcvNjY1ODM4OTgzLTM0NWI5Zjk3LTMwMjktNDJlZC04OGQ2LTQ0ZDYyMTViNDk0YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYxMDA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MTAwNVQxNTQ2MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05NjM3OGYxMDg3NDgwYmQwOTgwYjkyNzVkMjAwOWVlNzZlOTVhNTQ3OGVlZDE0MDA3NjNlYzliYTVhNjA4NTdkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.I_zz0AxzE7886jx2OF8tskwh5HOHCe2xQNb7SbyG2N0)
