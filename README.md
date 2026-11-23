# Grocery
Grocery inventory dataset
## Description 
This project described and evaluated the inventory of a grocery store. it was sourced from kaggle.com. it comprise of 17 fields (columns) and 572 observation (rows). it consisted of 5 unanswered questions meant to give data insights for future decision making.
## Data cleaning 
Data cleaning was done using power query. Simple text transformation was done and irrelevant columns was removed 
## Procedure 
this analysis was done using powerBI. Each questions was answered using data analysis expression (DAX). Firstly, a date table was created from the date received field. My_Date_table = CALENDAR(MIN('Grocery_Inventory new v1'[Date_Received]),MAX('Grocery_Inventory new v1'[Date_Received])), the table was then marked as a date table and merged on the date model view using 1- to many relationship 

## Questions and finings 
1. What is the average stock quantity available per product category?
   <img width="1116" height="614" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/60b28ec3-f700-4675-9e65-4f5ebc2b6328" />

3. Which suppliers contribute the most to total product inventory?
4. Which products have the longest shelf life before expiration, and how does that impact sales?
5. Which products are most likely to run out of stock based on last reorder levels? 
6. Can we predict seasonal demand for different product categories based on sales volume trends?
7. What are the optimal reorder levels for high-demand products to prevent stockouts? 

 
