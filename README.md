# Grocery
Grocery inventory dataset
## Description 
This project described and evaluated the inventory of a grocery store. it was sourced from kaggle.com. it comprise of 17 fields (columns) and 572 observation (rows). it consisted of 5 unanswered questions meant to give data insights for future decision making.
## Data cleaning 
Data cleaning was done using power query. Simple text transformation was done and irrelevant columns was removed 
## Procedure 
this analysis was done using powerBI. Each questions was answered using data analysis expression (DAX). Firstly, a date table was created from the date received field. My_Date_table = CALENDAR(MIN('Grocery_Inventory new v1'[Date_Received]),MAX('Grocery_Inventory new v1'[Date_Received])), the table was then marked as a date table and merged on the date model view using 1- to many relationship 

## Questions and finings 
