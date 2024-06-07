# Cyber-Gogi
This repository is for submitting the Peak AI hackathon challenge

What does this project do?
This project is aims to analyse data related to the sales, promotions and profits of various items through order numbers, customer segment and category. 

For Task 1, We categorised the sub categories by sales and total profit and produced bar charts from the analysis. The results show that the top 3 bestselling sub-categories are Chairs, Phones and Storage in that order. The top 3 best-profiting sub-categories are Copiers, Phones and Accessories in that order.


For Task 2, We took into account data on discounts in order to define what promotions have been applied. The data was ordered chronologically and only discount values > 0.2 were considered as a period of promotion. By doing so, we cna identify what periods of time are during a promotion and what periods aren't. The pre-promotional period was defined as the 7 days before a promotional period begins and the post-promotional period  From this dataset we used statistical technique known as a t-test to analyse the impact of these promotions on the sales.

For Task 3, we produced values on the purchasing frequency, order size and preferred product category by grouping together the UniqueIDS. Graphs are produced based on relevamt values coressponing to the different customer segments for analysis.

For Forecasting, we used various techniques including previous month sales, 3 month average sales and moving averages. From the data we used linear regression and attempted to use pycaret for AutoML.
