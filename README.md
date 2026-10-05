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


<img width="1400" height="544" alt="Screenshot 2026-10-05 at 16 14 32" src="https://github.com/user-attachments/assets/345b9f97-3029-42ed-88d6-44d6215b494a" />
