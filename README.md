# Chinese-Grocery-Store-Analysis
An analysis of sales data about vegetable sales at a grocery store.


## Task
The manager of a Chinese grocery store has asked the data team to evaluate sales trends of produce over the past 3 years.  The goal is to discover:
-	What are the key trends over the past three years?
-	What is the monthly growth rates?
-	What products tend to perform well?

## Data 
The data analyst has been provided with data regarding sales from 2020-07-01 to 2023-06-30 as well as item code information, loss rates of individual items, and wholesale prices.
(Source: https://www.kaggle.com/datasets/yapwh1208/supermarket-sales-data)

![image](https://github.com/user-attachments/assets/ff331bc3-dcfd-4b70-a818-62ce158447b6)

 
## Insights
### General Trends
-	The grocery store has been having an overall downward trend in sales over the past three years, with total sales dropping by 35% from 2021 to 2022.
-	The market appears to have season trends with sales increasing drastically in January and February, likely due to Lunar New Year celebrations, as well as around September and October, likely due to Mid-Autumn Festival celebrations.

![image](https://github.com/user-attachments/assets/0324f8d0-cc18-40d3-aaf0-32124f6777e5)


### Items by Performance
-	The top five performing items are: Broccoli, Net Lotus Root, Wuhu Green Peppers, Xixia Mushrooms, and Yunnan Shengcai.
-	Broccoli and Net Lotus Root are the two top performers and generally do well year round, Xixia Mushrooms appear to excel seasonally, specifically in the Autumn, around October.

![image](https://github.com/user-attachments/assets/8322595a-22b5-48ac-a413-cd3e83d377e0)
 
-	While these items tend to bring in the most profit over time, they also tend to rank among the highest returned items.
![image](https://github.com/user-attachments/assets/b054cec1-3a78-4de2-92d5-6cb88f977732)

 
### Return Rates
-	The overall return rates per year have fluctuated a bit, ranging from 4.2% to 6.1%, though typically lie around 5.25%.
 ![image](https://github.com/user-attachments/assets/254f0636-441e-4c8d-9ee3-690e177f7f38)

-	Return Rate and Loss Rate do not appear to be strongly correlated to one another as seen by the loss rates of the top 10 returned items
 
### Discount Rate
-	The discount rate of the store has increased year after year, starting as low as 2.38% of all items sold being sold at a discount in 2020 to 7.75% by 2023.
 ![image](https://github.com/user-attachments/assets/01d27a43-5009-45f7-8596-4f62c718a980)


## Questions for Further Analysis
### Questions for stakeholders
-	Is there data on stocking products that could be available for analysis as well as any data on when a product is out of stock?  This may help to better analyze how to mitigate loss rates.
-	In the future, it may be helpful to track individual transactions rather than just item sales in order to calculate Average Transaction Value.

