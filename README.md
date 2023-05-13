# FORESIGHT-PHARMACEUTICAL COMPANY SALES ANALYSIS
## Introduction
Here is a four (4) years sales analysis of Foresight pharmaceutical company. The company supplies its six (6) product classes to two (2) countries; Germany and Poland. Foresight does not sell directly to customers, instead, they work with Managers who supplies to Sales Rep which in turn work with couple of Distributors that supplies to two channels (Pharmacy and Hospital). Each Sales contributor shared their Sales Data to help the company gain insights up to retail level. This report dived deeper into understanding the overall sales trend of the company and also predict subsequent years sales trends. 
The data set was sourced from Foresight BI & Analytics.
## Project Task
To perform in-depth analysis into sales dataset and generate insights up till retail level.
## Skills/Concepts Used
•	Power Query Editor
•	DAX functions
•	Quick measures
•	Data Visualization
## Problem Statements
#### •	 What is sales revenue per year? Has there been an increase or decline in sales in each year?
#### •	Which product class was the best seller each year and also across the 4years trend?
#### •	Which distributor contributed the most to the sales revenue?
#### •	Which country had more sales across the year?
#### •	Are there more sales at Retail level compared to other sub-channels?
## Data Transformation
The dataset was transformed using Power Query Editor. The following inconsistencies were noticed;
#### •	The quantity and sales column had negative values. 
#### •	The quantity, sales and profit column has wrong data-type.
The negative values were changed to positive as there cannot be a negative quantity and the data types of quantity, profit and sales column was changed from text to whole number.
Date hierarchy was created to enhance drill-through on time-series charts for actionable insights.
## Data Visualization
Here is the company’s interactive sales report .
### Overview Page
The overview page explains in details the sales trend and revenue made by the various product classes and sales contributors (sales rep, distributors, channel and sub-channel) in 4years (2017-2020) in the two (2) countries.
#### •	Which sub-channel has the highest sales and least sales across four years? Which product class has the highest sales?
#### •	Which Sales team made the most and least sales?
#### •	Which Distributor made the most and least sales?
### OVERVIEW
![Overview page](https://github.com/DeesAnalytics/FORESIGHT-PHARMACEUTICAL/assets/124782621/4a0f718d-4e50-4f1e-8b53-7855e6f0f325)

### Product Performance Evaluation
This page dive deeper into understanding the sales trend for each year.
#### •	What is the effect of price on sales quantity?
#### •	The sales team with best and least sales
#### •	Product sales revenue by class.
#### •	Are there  likely to be  more sales of a product class in a particular month?
### PERFORMANCE EVALUATION
![DashboardX](https://github.com/DeesAnalytics/FORESIGHT-PHARMACEUTICAL/assets/124782621/2d6c36a2-5842-4c4d-b22c-ebc633d87059)

## Actionable Insights
#### •	Foresight company generated a total of $12.09bn in four years. Year 2018 had the highest sum of sales revenue with $3.58bn and lowest in 2017 with $2.73bn. 
#### •	The steepest decline in sales happened between 2018 and 2019 as sum of sales revenue dropped from $3.58bn to $3.0bn. Three factors contributed to the decrease : 
##### •	i: Poland which only operated in 2018, contributed 19% of the total sales in 2018.
##### •	ii: There were a total of 26 distributors in 2018 and 10 in 2019
##### •	iii: Top distributor (Geriach-LLC) had a 25% decrease in sales.
#### •	The greatest anomaly in four (4) years occurred in August 2019 where $491M sales revenue was generated. This was contributed by distributor Bashirian-Kassuike who generated 53.79% of the total sales while Analgesic contributed 35.7% of the sales revenue.
#### •	Two distributors (Kross and Geriach-LLC) has contributed more sales revenue over the years with Geriach-LLC having highest sales in year 2017 and 2018 while Kross has the highest in year 2019 and 2020.
#### •	The 2.94% year to year sales growth in Germany dropped to -1.91% in 2020. The drop was contributed by the top distributors; Kross whose sum of sales changed from $1.01bn to $904M and Gerich sales revenue dropped from $874M to $845M.
#### •	Product class analgesics, antiseptic and mood stabilizers have good sales performance over the years with Anti-malarial being the least.
#### •	They were a total of 29 distributors in four years, with 26 distributors in year 2018 and 7 distributors in 2020.
#### •	Retail pharmacies and Government hospitals have contributed more to the sales team over the year.
#### •	Manager Britanny Bold of Delta sales team have more consistency in generating sales revenue while James Goodwill of Alfa sales team as the least.
## Recommendations
#### •	Operations should begin in earnest in Poland has it is a promising country for Foresight Company. A total sales of $641M was generated from Poland in the only year it operated. This will help generate more sales to the company and also reduce unemployment rate.
#### •	Fore-sight should conduct research to understand why distributors leave. Distributors are key contributors to sales.
#### •	There should be more distributors in Germany has it has experienced a decrease in distributors over the years with 14 in 2017 and 7 distributors in 2020.
#### •	The distributors should be compensated during the peak months of sales.
#### •	Incentives should be given to the sub-channels.
#### •	Promotional campaign should begin for Anti-malarial, Anti-piretics and Anti-biotics.
#### •	Vocational trainings should be organized for Sales team.

