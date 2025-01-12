# Cafe Sales Analysis Project

## 1. Background and Overview

This project aims to analyze the performance and sales trends of coffee shops in 2023, using sales records and additional supplemental datasets. The goal is to uncover valuable insights that can help improve business operations, and profitability. The analysis was performed through [exploratory data analysis (EDA)](EDA/EDA.ipynb) in Excel and Python, and the results were visualized using an interactive [Tableau dashboard](https://public.tableau.com/app/profile/kensuke.umakoshi/viz/coffee_17365392664280/Dashboard1), providing a comprehensive view of key performance indicators (KPIs) like Sales Growth Rate, Average Transaction Value, and Gross Profit Margin.

#### Primary KPIs: 
- Sales Growth Rate 
- Average Transaction Value
- Gross Profit Margin

#### Tools:
- Excel
- Tableau
- Python 
- Jupyter Notebook

## 2. Data structure
![alt text](image/ER.png) 

### Sales Table:
- The central table, capturing details about transactions, including store information, products sold, and their pricing. Provides data for analyzing sales trends, product performance, and shop performance in sales.

### Weather Table:

- Contains weather-related information (e.g., temperature, rainfall) for different store locations on specific dates. Helps in understanding how weather conditions impact sales patterns.

### Holiday Table:
- Includes a list of holidays and their dates. Useful for assessing the effect of holidays on sales performance.

### Cost Table:
- Contains cost-related data for various items. Enables profitability analysis by combining cost data with sales figures.

## 3. Summary 3-4 sentence
- From January to June, sales decreased by 38%. In spite of this, sales gradually increased after June, showing a 40% increase by December.

- Coffee and Tea are the top-performing categories, which have low gross profit and top order quantity. Coffee beans category has greatest gross profits, however contribute only 8.5% of profits.

- Astoria (store_id 3) performed contantly, however, Lower Manhattan(store_id 5) and Hell's Kitchen (store_id 8) decreased sales in June 30% and 33%, respectively.

- The clear weather led to an increase in profit of 5%

## 4. Insights deep dive: [Jupyter Notebook](EDA/EDA.ipynb)
Coffee and tea are the most top-performing categories, contributing 35% and 25% to overall sales, respectively. In contrast, coffee beans and branded categories, despite generating significant gross profits, contribute only 8.5% and 3.7%.
![alt text](image-4.png)
![alt text](image-3.png)


In terms of store performance, Astoria (store_id 3) consistently achieves steady sales, while Lower Manhattan (store_id 5) exhibits the highest performance gap. Notably, Lower Manhattan and Hell's Kitchen (store_id 8) experienced significant sales drops in June, with declines of 30% and 33%, respectively.
![alt text](image-1.png)

Regarding the impact of weather on performance, clear weather leads to an average sales increase of 5% compared to periods with rain or snow.
![alt text](image-2.png)

Time influences the sales 
![alt text](image.png)
## 5. Recommendations


