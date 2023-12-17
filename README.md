# fer-nandes13-Final-Project-2023
Bootcamp Final Project
https://public.tableau.com/app/profile/erico.fernandes/viz/Book1_17026074676570/Sheet112?publish=yes


This readme.file contains information of Adidas Sales Dataset in United States
This Adidas sales dataset is a collection of data that includes information on the sales of Adidas products between January 1st 2020 and December 31st 2021(Covid-19 Highest Peak.) This type of dataset may include details such as the number of units sold, the total sales , the location of the sales, the type of product sold, and any other relevant information.

This Adidas sales data can be useful for a variety of purposes, such as analyzing sales trends, identifying successful products or marketing campaigns, and developing strategies for future sales. It can also be used to compare Adidas sales to those of competitors, or to analyze the effectiveness of different marketing or sales channels.

About the Dataset
14 Columns

Retailer: Name of the Retailer, retailing adidas Men's/Women's Athletic Footwear/Street Footwear and Men's/Women's Apparel.

Retailer ID

Invoice Date: AKA date of the purchase

Region: In the US

State: 50 states in the US

City: In the US (more or less 52 cities)

Product: Men's and Women's Athletic Footwear and Street Footwear and Men's and Women's Apparel

Price per Unit: of product per region,city,state

Units Sold: of product per region,city,state

Total Sales

Operating Profit

Operating Margin

Sales Method: 'In-store' 'Outlet' 'Online'.


The jupyter Notebook

1- First starts by looking at the data

2- Finding existence of Null values , missing date or duplicates and general look at unique values.

3-Verifying the range of date covered by the dataset

4-Basic analysis to check data types

5-General formatting , column drop due to redundancy and lack of relevancy significance.

6-Data converting process of the column invoice_date to datetime64[ns]

7-Starting the process of Data wrangling: Trying to obtain simplicity through some approaches of column combining and transformation in order to explanatory relevance from the aimed columns for combining and transformationing.

8- Continuing the exploratory Analysis by focusing on numerical and categorical data

9- Plotting numerical data to verify data distribution and possible outliers

10- Plotting categorical variables to verify data distribution and others aspects

11- First Ananlysis on the relevancy: looking at the correlation what can they explain in a further regression model.

----------------------------------------------------------------------------------------------------------------------------
12 _ Exaustive Exploratory Analysis through plotiting and several tables and pivot tables some of them were just tests and different approaches.
What follows are several tables , pivot tables and plots to understand which were the top selling products, most/less profitable cities. Tables for Top retailers working with adidas in 2020-2021. Plots also for preferred selling methods, and many other pivot tables for number of units solds price per unit among per invoice date , selling unique methods per state , product , total sales and operating_profit.

13- Required API to include in the project : API on US date holidays to compare with the dates in the adidas dataset.
13.1 Preparing the data retrieved through API , transformations using json method 

14. Continuing Exploratory analysis through tables and pivot tables and API.

15. Building Regression model to predict target total_sales
