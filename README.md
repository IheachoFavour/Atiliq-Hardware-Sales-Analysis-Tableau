# Atliq Hardware Sales Analysis

## Table of Contents
- [Project Introduction](#project-introduction)
- [Structure of the dataset](#structure-of-the-dataset)
- [Tools and Techniques](#tools-and-techniques)
- [Key Accomplishments](#key-accomplishments)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Modelling](#data-modelling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Some Inferences and Conclusions](#some-inferences-and-conclusions)
- [Visualisation in Tableau](#visualisation-in-tableau)
- [Recommedations](#recommedations)

## *Project Introduction*
The sales director of Atiliq hardware is concerned with the sales and profit trend over the past four years. He suspects sales and profits are declining and he cannot track where exactly the business is failing. He does not have data insights.

## *Structure of the dataset*
- Transactions: This table lists information about a transaction. A record of a transaction contains product code, customer code, market code, order date, sales quantity, sales amount, profit, profit percentage and cost price
- Customers: This table contains customer code, customer name and customer type.
- Date: This contains information about the date, month name and year a transaction was carried out.
- Products: This contains product code and product type.
- Market: This contains market code, name and zone.

## *Tools and Techniques*
- Sql for inserting the data into tables.
- Tableau for data visualisation. [View Here](https://public.tableau.com/app/profile/favour.iheacho/vizzes)

## *Key Accomplishments*:
- Identified that the significant underperformance of market stores in Bengaluru, Bhubaneshwar, Surat, Lucknow, and Patna, both in terms of total sales and sales quantity, is a major contributor to the overall declining sales trend.
- Discovered that the significant difference in sales between the peak months (January, March, November) and the low months (September, July, August) suggests that the business may be heavily influenced by seasonal factors, which could be impacting the overall sales performance.
- Provided data-driven insights to the sales director to better understand the financial health and performance of the business across different product types, customer segments, and regional markets
- Developed a comprehensive dashboard to enable the sales director and other stakeholders to continuously monitor the key performance indicators and make data-informed decisions going forward.

## *Data Cleaning and Preparation*
- Sales Amount: A new column - Normalised Sales Amount was created because there were two amounts in USD which were converted into Indian Rupees.
- Market: The two market stores outside India - New York and Paris were removed.

## *Data Modelling*
- Fact table: Transactions
- Dimensions table: Customers, Date, Products and Market
![image](https://github.com/user-attachments/assets/5ce64429-f12f-4dba-82e5-28fb587d2f68)

## *Exploratory Data Analysis*
- Analyzed the overall sales and profit trends over the past 4 years
- Best and worst performing market in terms of sales, sales quantity and profits.
- Best and worst performing customers in terms of sales and profits.
- Analysed sales by product type, zone and customer type.
- Discovered significant differences in sales between peak months (January, March, November) and low months (September, July, August).

## *Some Inferences and Conclusions*
- Year 2018 had the highest sales of 403.6M while Year 2017 had the lowest sales of 91.4M.
- Delhi NCR market store remained the best performing market with a total sales of 519.6M and Bengaluru was the worst performing market with a total sales of 0.4M
- The top 3 peak months are January, March and November with total sales of 91.7M, 91.1M and 90.9M respectively. The months with the least amount of sales are September, July and August with total sales of 53.8M, 69.6M and 70.8M.
- Year 2019 has the highest profit of 10.48M although Year 2018 had the highest sales. Year 2020 has the lowest profit of 2.0M although Year 2017 has the lowest sales. 
- Surat market store has the highest profit percentage of 4.87% although Delhi NCR had the highest sales. Bengaluru remains the market store with the lowest profit percentage and lowest sales of -20.78% and 0.37M respectively.

## *Visualisation in Tableau*
![image](https://github.com/user-attachments/assets/4cc1192b-f496-48bb-9f9e-29a708a1e8d7)

![image](https://github.com/user-attachments/assets/9fe8827e-641d-41eb-836b-8f217a33aa46)

## *Recommedations*
- Investigate underperforming stores, customers, and regions - develop targeted strategies to improve their performance
- Analyze seasonal sales patterns and develop mitigation strategies for low-performing months
- Explore opportunities to expand own-brand products and grow ecommerce sales
- Develop a balanced geographical strategy to ensure consistent sales across regions
- Analyze cost trends, pricing, competition, product mix, and customer channels to understand profit decline
