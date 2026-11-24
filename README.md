# Grocery - powerBI
Grocery inventory dataset
## Table of content
- [introdcution](#introduction)
- [project objecrives](#project-objectives)
- [Description of dataset](#description-of-dataset)
- [Tools](#tools)
- [Data cleaning](#data-cleaning)
- [KPIs](#kpis)
- [Research Questions](#research-questions)
- [Key Findings](#key-findings)
- [Recommendation ](#recommendations)
- [Conclusion](#conclution)

## Introduction
This project is described and evaluated in the inventory of a grocery store.
## project objectives 
this project is intended to provide insights into the inventory of a grocery store, as a means to influence future decision-making
## Description of Dataset
The dataset was sourced from kaggle.com. It comprises of 17 fields (columns) and 572 observations (Rows). It consisted of 5 unanswered questions meant to give data insights for future decision making.
## Description 
This project described and evaluated the inventory of a grocery store. it was sourced from kaggle.com. it comprise of 17 fields (columns) and 572 observation (rows). it consisted of 5 unanswered questions meant to give data insights for future decision making.
## Data cleaning 
Data cleaning was done using power query. Simple text transformation was done and irrelevant columns was removed 
## Procedure 
this analysis was done using powerBI. Each questions was answered using data analysis expression (DAX). Firstly, a date table was created from the date received field. My_Date_table = CALENDAR(MIN('Grocery_Inventory new v1'[Date_Received]),MAX('Grocery_Inventory new v1'[Date_Received])), the table was then marked as a date table and merged on the date model view using 1- to many relationship 

## Questions and finings 
1. What is the average stock quantity available per product category?
2. the average stock quantity was measured using avg stock quantity
3. AVERAGE('Grocery_Inventory new v1'[Stock_Quantity])
   <img width="1116" height="614" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/60b28ec3-f700-4675-9e65-4f5ebc2b6328" />
seafood leads in stock avalaibility, while grains have the lowest. Future purchases should priortize grains to meet demand.
4. Which suppliers contribute the most to total product inventory?
<img width="1107" height="616" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/611b85b4-852d-4e4f-9664-b1e98b248ed6" />
Katz, twitterwire, meevee, quartz and feedfire are our most prominent suppliers.
5. Which products have the longest shelf life before expiration, and how does that impact sales?
6. Which products are most likely to run out of stock based on last reorder levels? 
7. Can we predict seasonal demand for different product categories based on sales volume trends?
8. <img width="1086" height="609" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/ecf3aa32-aa87-4085-b63c-d20d02717ed0" />

9. What are the optimal reorder levels for high-demand products to prevent stockouts?
10. Reorder for high demand be improved by 50% 

 
