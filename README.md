# 💰 A Visionary Dashboard of Sales Analytics

## Description:
The sales dashboard provides an overview of business performance, including key metrics such as total revenue, orders, and products. Users can explore sales trends by year, month, and country. Additionally, a product analysis section highlights specific product performance and Trend Analysis.

## 🎯Key Features:
 The key points from the dashboard  shared:

#### ➡️Overview:
The dashboard provides an overview of sales data from 2020 to 2023.
Key performance indicators (KPIs) include Year to Date (YTD), Quarter to Date (QTD), and Month to Date (MTD) figures.
The date range is from January 1, 2020, to December 31, 2023.
#### ➡️ Product Sales:
A table lists various products and their sales figures for YTD, QTD, MTD, and Previous Year (PY).
Products include Almond Croissant, Apple Juice, Brownie Bites, Chicken Salad Sandwich, Chocolate Chip Cookie, and more.
#### ➡️Trend Over Country:
A bar chart visualizes sales trends across countries (e.g., Colombia, Denmark, Egypt).
Each country’s sales are represented by bars.
#### ➡️ Daily Trend:
A line graph shows sales trends over time within the specified period.
#### ➡️Total Revenue:
The total revenue for the given period is summarized.

## 🖊️Highlighted DAX Function:

#### 📜Year To Date
YTD = TOTALYTD(SUM('Sales 2021-2023'[Amount]),'Sales 2021-2023'[Date].[Date])
#### 📜 Month To Date
MTD = TOTALMTD(SUM('Sales 2021-2023'[Amount]),'Sales 2021-2023'[Date].[Date])
#### 📜 Quater To Date
QTD = TOTALQTD(SUM('Sales 2021-2023'[Amount]),'Sales 2021-2023'[Date].[Date])
#### 📜Total Revenue
Total Revenue = SUM('sales 2020-2023'[Amount])
#### 📜Date Function
1.WEEK NAME= "week" & WEEKNUM('Sales-2020'[Date].[Date])
2.Week Number = WEEKNUM('Sales-2020'[Date].[Date])
3.Quater = "Q" & FORMAT('Sales-2020'[Date].[Date], "Q"
4.DAY = "DAY" & FORMAT('sales-202O'[Date].[Date],"D")

## 📊Visuals Included:
➡️Charts displaying Sales by Year, Month, Week, Day.
➡️ Funnel map shows the total Sales by Country.
➡️ Charts display the trend by country and Yearly, Quater, and Monthly Trends based on Time Intelligence 
➡️ Table View describes the Product based on YTD, MTD, QTD, and Total Revenue.
➡️Line Chart for Trend Analysis for YTD,MTD,QTD .

## ⛳Conclusion:
This analysis provides valuable Sales insights Worldwide. Power Query and Power BI can draw powerful insights from raw datasets, Which will be more Valuable To Business Users.


#### Sales Dashboard 2020-2023
![Overview](https://github.com/anitharamesh022/A-Visionary-Dashboard-of-SalesAnalytics/assets/164473616/3ec6e324-2cea-4d13-af83-25e0e875f18b)
![YTD](https://github.com/anitharamesh022/A-Visionary-Dashboard-of-SalesAnalytics/assets/164473616/534bb2a2-3e5b-4e73-88ef-6c588b66c5e6)
![QTD](https://github.com/anitharamesh022/A-Visionary-Dashboard-of-SalesAnalytics/assets/164473616/41d52022-2d3d-4841-a020-1e6944a8eb10)
![MTD](https://github.com/anitharamesh022/A-Visionary-Dashboard-of-SalesAnalytics/assets/164473616/54cf64ac-f4e7-478f-819f-c902636eee92)


