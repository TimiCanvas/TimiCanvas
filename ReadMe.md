# Retail Store Analysis
![](retail_store_image.jpg)

## Introduction
In this analysis I investigated a hypothetical 'XYZ' retail store. The report and dashboard produced from this analysis was submitted  and presented by me at the Data Analytics and Modeling conference 2023 hosted by DBrownConsulting in Lagos, Nigeria, where my team (conprising myself and two others) won the Datathon competition. 
The dataset (a csv file) was provided by DBrownConsulting, is present in this repository, and can be accessed [here](Retail_Analytics.csv).
[Dataset Screenshot](dataset_screenshot.PNG). The dataset consist of 9,995 rows and 11 columns with columns such as Order date, Sales, Profit, Discount amongst others.
![](retail_store_image.jpg)

## Problem Statement
The aim of this project is to show my strength in data preparation, modeling, visualization, insights, pattern finding, storytelling and recommendations. This analysis answerred questions such as:
1. Is the current year 2018 the most successful yet?
2. What product accounts for sale and profit increase?
3. Which city is generating the most profit for the current year?
4. What is the year-on-year analysis of the businesss with respect to sales and profit?

## Data Preparation and Transformation
The dataset underwent preprocessing and was found to be already clean,the datatype of each column was checked and corrected where needed.  
A measure table was created to house calculations (using Dax) such as calculated columns, calculated measures, calculated date columns and YOY calculations.
The star schema concept was applied and the data normalized into a retail fact table, and three different dimensions table named location table, customer table and category table.
Finally, a date table called the calendar table was created to include columns such as: year, year month, year month number, quaters, month, month number.

![Dataset snapshot](dataset_snapshot.PNG)
![Retail facts table](fact_table.PNG)
Customer dimension table | Location dimension table
-----------------------  | -----------------------
![Customer dimension table](customer_table.PNG)!| [Location dimension table](location_table.PNG)

Category dimension table | Calendar dimension table
-----------------------  | -----------------------
![Category dimension table](category_table.PNG) | ![Calendar dax measure](calendar_table_dax.PNG)

![Data Star Schema](data_model.PNG)

## Data Visualizations

Snapshots of the overview, sales, profit page are shown below.

![Overview page](overview_page.PNG)
![Sales analysis page](sales_analysis_page.PNG)
![Profit analysis page](profit_analysis_page.PNG)

## Insights
* The current year 2018 has been noted to be the company's most successful year yet, pulling 50% of the total cumulative sales of previous years. 
* Health drinks and soft drinks which accounted for the most sales across all the years retained their spot as the company's highest selling and  most profitable products.
* The city of Kanyakumari generated the most profit for the year 2018 leaping from its fourth profitable spot in the previous year.
* It was noticed that the company's profits peaked in 2016, and dropped significantly in 2017 before rising in 2018.
* Fish sales accounted for products where we noticed the highest profit margin with almost 2% highest than the inventory average of 27%

## Recommendations
* An increase in marketing and investment in Fish product for the coming year.
* Sales approach and strategy of our store in the city of Kanyakumari should be employed in our other stores.
* An expansion of the existing store in Kanyakumari, or opening of more branches in said city.
* Marketing and sales strategy used for Health and Soft drinks should be applied to other products.

