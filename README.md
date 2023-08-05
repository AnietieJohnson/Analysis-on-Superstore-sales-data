## Introduction
As we stand at the threshold of a new business year, the path forward demands a keen understanding of sales performance from the preceding year. To navigate this journey effectively and make informed decisions, we embark on a data analysis project that will unearth valuable insights. By scrutinizing specific segments, quarters, months, products, and cities, we seek to pinpoint areas of significance. This project's ultimate goal is to equip us with the strategic insight required to enhance performance and elevate decision-making in the year ahead.
## Problem Statement
I am required by Superstore's manager to analyze and review sales data for the past year to improve 
performance in the coming. The following questions are to be answered.

 1. What category of Product gave highest Profit and sales
 2. Show profit and sales trend by quarter, How does discount differ quarterly
 3. Show profit and sales trend by month
 4. Which are the Top Four cities by sales
 5. Bottom Four cities by sales
 6. What shipping method was most covenient for customers

## Data Sourcing
The data was provided to me via google drive, It contains one sheet with 9995 rows(one of which is the column names) and 21 columns. The column headings are as follows: **Row ID,** **Order ID,** **Order Date**, **Ship Date**, **Ship Mode**, **Customer ID**, **Customer Name**, **Segment**, **Country**, **City**, **State**, **Postal Code,** **Region,** **Product ID,** **Category,** **Sub-Category,** **Product Name,**, **Sales,** **Quantity,** **Discount** and **Profit**.
## Raw data
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/superstore%20Raw%20data.png)
## Solutions
#### Focusing on the following Key Performance indicators:
###### Sales
###### Discount
###### Quantity
###### Profit

I used Pivot Table and charts to better explain my insights for each  question.
- I created the pivot table by Selecting the data range
- Then from the **_Insert tab_** I chose PivotTable and set it to new worksheet.
- Chose a fitting field for Rows field and for Values Field
- For charts, I created each by using **_pivot table analyze_**
- Column chart that gave the best representation.
### Question 1:
Category of Product that gave highest Profit and sales
**Technology** with a total disount lower than the other categories, generated the highest Profit and Sales. Furnitures generated the least profit but had a higher sales than office supplies.

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Total%20Profit%20and%20sales%20by%20Category%20A.png)     |    ![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Total%20Profit%20and%20sales%20by%20category%20B.png)
:-------------------------------------------------------------:|:------------------------------------------------------------:
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Profit%20and%20Sales%20by%20category%20visuals.png)

### Question 2:
Show profit and sales trend by quarter, How does discount differ quarterly, Quarter 4 generated more sales and more profit.

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Varying%20trend%20of%20KPI%20by%20Quarter%20A.png)     |    ![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Vary%20Trend%20of%20Kpi%20per%20quarter%20B.png)
:--------------------------------------------------------------------:|:--------------------------------------------------------:
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Kpi%20trend%20by%20quarter%20visuals.png)

### Question 3:
Show profit and sales trend by month
Having seen the trend of sales across quater, it is important to know what month sales peaked in the quarter.

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Sum%20of%20sales%20and%20profit%20by%20Month.png)

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Trend%20of%20sales%20and%20profit%20per%20month.png)

### Question 4:
Which are the Top Four cities by sales
I narrowed my analysis down to the Cities that are contributing the highest to company's sales and returns

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Top%20performing%20cities%20by%20sales%20and%20profit.png)

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Bottm%20Four%20Cities.png)

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Top%20Four%20cities%20visuals.png)

### Question 5:
Bottom Four cities by sales
There is a need to understand areas of focus for improvement, Hence the analysis of Low performing states

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Bottom%20Performing%20cities%20by%20sales%20and%20profit.png)

### Question 6:
What shipping method was most covenient for customers

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/customer's%20preferred%20mode%20of%20shipping.png)

![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/Shipment%20mode.png)

## Adding Ship Mode as slicer
![](https://github.com/AnietieJohnson/Analysis-on-Superstore-sales-data/blob/main/shipment%20mode%20as%20a%20suitable%20slicer.png)

## Conclusion
The analysis underscores Newy york's remarkable performance, as it dominated sales and profit. Nevertheless, certain Cities experienced substantial profit setbacks, particularly in specific product lines. Notably, technology stood out as prolific revenue generator. A significant proportion of customers favored the standard class shipment for their orders. Furniture as a category generates more sales but has the lowest Returns. Also to be noted is the fact that some discounts don't directly encourage sales. I recommend the following:

- Market insights and surverys to understand reasons for low sales in certain cities
- Advertisement and product awareness campaigns to encourage sales.
- Cutting down discount on product that dont generate income
- Revisitting cost of production for items in furniture category
- Check cities with high sales performance, implement their strategies in other cities.
