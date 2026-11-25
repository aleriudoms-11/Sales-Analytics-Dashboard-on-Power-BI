# Sales-Analytics-Dashboard-on-Power-BI
Sales Analytics Dashboard in Power BI provides interactive visualisations and actionable insights into sales performance. Track revenue, profit, sales trends, regional performance, customer behaviour, and product metrics using dynamic KPIs, DAX calculations, and drill-through reports to support data-driven business decisions.

The dashboard enables users to monitor key business metrics such as total revenue, profit, sales growth, customer segmentation, product performance, and regional sales trends. Interactive filters and drill-through capabilities allow stakeholders to explore data at multiple levels and make data-driven decisions with confidence.

Key Features
📊 Interactive sales performance dashboard
💰 Revenue, profit, and margin analysis
📈 Monthly and yearly sales trend tracking
🌍 Regional and geographical sales insights
🛍️ Product category and top-performing product analysis
👥 Customer segmentation and purchasing behaviour insights
🎯 KPI monitoring with dynamic visualisations
🔍 Drill-down reports and advanced filtering options

Technologies Used
Microsoft Power BI
Power Query (ETL & Data Transformation)
DAX (Data Analysis Expressions)
Excel / CSV Data Sources

This repository demonstrates how Power BI can be leveraged to transform business data into meaningful insights, helping organisations optimise sales strategies, identify growth opportunities, and improve overall performance.

1) How to design a dashboard in Power BI?
2) Data modelling with Power BI and star schema development
3) Identifying measures and KPIs for sales analytics
4) Creating measures and setting up a dedicated measure table
5) Time intelligence calculations in Power BI - MoM changes
6) Using the "new" card visual and reference labels
7) Fixing problems with DAX measures
8) Using Field parameters to create a dynamic trend chart
9) "Group" feature of Power BI to make histograms
10) Working with ZOOM SLIDER
11) Gauge chart to see Profit and LBS %
12) Table design in Power BI
13) Conditional formatting for tables
14) Bookmarks
15) Fixing problems with bookmarks - data / filter preservation
16) Setting up tooltips for country breakdown
17) Slicer panel set up in Power BI




Step 1. Data modelling with Power BI and star schema development

Connect the tables accordingly and create a Star Schemma

Step 2. DAX Measures

- Calculate different KPIs
  
1) Total Sales
2) Total Boxes
3) Total Shipments
4) Total Cost
5) Total Profit
6) Profit %
7) Low Box Shipments count (Sample boxes < 50)
8) Low Box Shipments %
9) Month on month changes
10) Year on year changes

To setup the calculations, go to HOME --> ENTER DATA --> Create the name "_Measures" --> LOAD

(16.New Measure.png)
(17.New measure table created.png)
(18.Create New measure within _Measures.png)
(19.Run the formulae and measure settings.png)
(20.Add a card to show total sales.png)
(21.Create Total Boxes formulae and delete column1.png)
(22.Create Total shipments formulae.png)

To create the Total Cost calculation, we need to: go back to the TABLE VIEW --> click on SHIPMENTS TABLE --> NEW TABLE

(23.Add new column on shipment table)
(24.New column cost created.png)
(25.Multiply by number of boxes.png)
(26.New measure Total Costs.png)
(27.New Measure Total Profits.png)
(28.New Measure Profit Percentage.png)
(29.First insights & visuals of the data.png)
(30.Profit percentage by product chart.png)
(31. First Insight.png)














