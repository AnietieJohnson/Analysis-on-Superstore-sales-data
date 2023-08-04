## Introduction
As we stand at the threshold of a new business year, the path forward demands a keen understanding of our company's sales performance from the preceding year. To navigate this journey effectively and make informed decisions, we embark on a data analysis project that will unearth valuable insights. By scrutinizing specific segments, quarters, months, products, and cities, we seek to pinpoint areas of significance. This project's ultimate goal is to equip us with the strategic insight required to enhance performance and elevate decision-making in the year ahead.
## Problem Statement
We are required by the manager to analyze and review sales data for the past year to improve 
performance in the coming. The following questions are to be answered.
1.	Total sales, profit and discount
2.	Average profit and average sales for the year
3.	Highest profit and highest sale value in the year
4.	Locate product, city and month that gave the highest of Sale and Profit
5.	- What category of Product gave highest Profit, do same for sub-category
    - What category of Product gave highest sales, do same for sub-category
    - Which Category has the highest quantity
  	- What is the relationship between discount and quantity
    - Which are the Top and bottom Four cities
6.	Show profit and sales by month, do same for Quarter. 

## Data Sourcing
The data was provided to me via google drive, It contains one sheet with 9995 rows(one of which is the column names) and 21 columns. The column headings are as follows: **Row ID,** **Order ID,** **Order Date**, **Ship Date**, **Ship Mode**, **Customer ID**, **Customer Name**, **Segment**, **Country**, **City**, **State**, **Postal Code,** **Region,** **Product ID,** **Category,** **Sub-Category,** **Product Name,**, **Sales,** **Quantity,** **Discount** and **Profit**.
## Raw data
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/superstore%20Raw%20data.png)
## Solutions
### Question 1:
- To get **_total sales_** for the year, I applied the **SUM FUNCTION** i.e =SUM(T2:T9995) to sum up the entire Sales column.
Superstore sold a total of **$ 2,297,201** worth of product for the year
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/total%20sales.png)

- To get **_total Profit_** for the year, I applied the **SUM FUNCTION** i.e =SUM(W2:W9995) to sum up the entire Profit column.
Super store made a profit of **$ 286,397** for the year
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Total%20profit.png)

- To get **_total Discount_** for the year, I applied the **SUM FUNCTION** i.e =SUM(V2:V9995) to sum up the entire Discount column.
  Super store gave a total discount of **$ 1,561** in the year.
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/total%20discount.png)
### Question 2:
- To get **_Average sales_** for the year, I applied the **AVERAGE FUNCTION** i.e =AVERAGE(T2:T9995), this takes the average of total values in the sales column.
On average superstore was selling atleast **$ 229.86** worth of product daily
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Average%20sales.png)

- To get **_Average Profit_** for the year, I applied the **AVERAGE FUNCTION** i.e =AVERAGE(W2:W9995), this takes the average of total values in the Profit column.
On average superstore Made a profit of atleast **$ 28.66** on sales made daily
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Average%20profit.png)
### Question 3:
- To get **_Highest sale_** within the year, I applied the **MAX FUNCTION** i.e =Max(T2:T9995), this function looks through the Sales column and returns the highest value sold. **$ 22,638** returned as the  highest sale value within the year.
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Highest%20sales%20value.png)

-  To get **_Highest Profit_** within the year, I applied the **MAX FUNCTION** i.e =Max(W2:W9995), this function looks through the Profit column and returns the highest profit value. **$8,400** returned has the highest profit value made within the year
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Highest%20provit%20value.png)
### Question 4:
#### Product, City and Month that generated the highest Sales
- To locate the **_product_** that gave the highest sale, I used **LOOKUP FUNCTION, (VLOOKUP)** I.E =VLOOKUP($AB$7,$E$2:$S$9995,15,0), it searches for a value in the leftmost column of a table and returns a related value from a specified column. 
Vlookup looks from left to right so I had to reposition my sales column, placed it on the left end of the product column before applying the formular. This means _Cisco TelePresence System EX90 Videoconferencing Unit_ was sold at $22,638 and it is the product that sold at the highest rate in the year.
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Product%20that%20generated%20highest%20sale%20value.png)

- To locate the **_City_** that that gave the highest sale, I used **LOOKUP FUNCTION, (VLOOKUP)** I.E =VLOOKUP($AB$7,$E$2:$S$9995,8,0)
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/City%20that%20generated%20the%20highest%20sale%20value.png)

- To locate the **_Month_** that that gave the highest sale, I used **LOOKUP FUNCTION, (VLOOKUP)** I.E =VLOOKUP($AB$7,E2:Y9995,21,0)
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Month%20with%20the%20highest%20sale%20value.png)

#### Product, City and Month that generated the highest Profit
- To locate the **_product_** that gave the highest Profit, I used **LOOKUP FUNCTION, (VLOOKUP)** I.E =VLOOKUP($AB$7,$E$2:$S$9995,15,0), it searches for a value in the leftmost column of a table and returns a related value from a specified column. 
Vlookup looks from left to right so I had to reposition my Profit column, placed it on the left end of the product column before applying the formular. _Canon imageCLASS 2200 Advanced Copier_ generated  $8,400 as profit, it is the product that generated highest profit within the year.
