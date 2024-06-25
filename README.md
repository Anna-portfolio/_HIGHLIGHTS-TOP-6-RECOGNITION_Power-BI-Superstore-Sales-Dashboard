**SUPERSTORE SALES DATASET**<br>
**[Update June 26, 2024]: Dashboard nominated for the Top 6 submissions in a global Power BI competition organized by the current employer (total number of participants: over 2'000)**<br>
Dashboard uploaded herein does not include any confidential, company-specific etc. data <br><br>
![profitoverview](https://github.com/Anna-portfolio/Power-BI-Superstore-Sales-Dashboard/assets/75646880/9c4edea3-2ed9-471a-8485-518341a18843)
<br><br>
**Data Overview**
- Table #1 Measures Table: stores DAX measures in a separate table (good practice)
- Table #2 Dashboard Description: list of what was done in this project
- Table #3 Orders: insight into orders placed by the customers
- Table #4 People: list of persons in charge of given regions
- Table #5 Returns: details of returned orders

**Pages Overview**
- Page #1 Cover: dashboard's cover with the title
- Page #2 Dashboard Decription: an illustrative overview of what was done in this project (in a form of a separate dataset; over 50 actions done)
- Page #3 Profit Overview: total profit analysis with a breakdown into categories, sales, regions and states
- Page #4 Region Overview: detailed view of a chosen region, specifying profit, total quantity of sold items, and sum of profit by order date
- Page #5 Orders - Top 5 States: data narrowed down to top 5 states, ranked by total order quantity
- Page #6 Q&A: page including Q&A section, giving insight into the questions which may be asked in regard to the analysed dataset
<br>

**What was done in this Dashboard**<br>
**Dataset Modification, i.a.:**
- add extra column with conditional split ([Orders]Discount Value)
- columns split, in order to visualize data in a more clear way (i.a. over [Orders]First Name and Last Name)
- format change: adjustments to visualize data in a more clear way (i.a. [Orders]Profit round to 2 decimal places, [People] set first row as header)

**Bookmarks:**
- Page #5: "Total Sales and Sales Target," unhiding a column chart incl. DAX measures
- Page #3: "Technology West," narrowing down the results to Technology category for West region

**Drillthrough buttons, i.a.:**
- Page #3: "Click for Region Details," directing to Page #4 for details per region

**DAX measures:**
- Page #3: visual "Avg Profit Target for 2025," using AvgProfit and AvgProfitTarget Measures (AVERAGE() function)
- Page #5: visual "Total Sales and Sales Target by State," using Sales and SalesTarget Measures (SUM() function)

**Filters:**
- Page #5: filter to narrow the dataset down to top 5 States per orders quantity

**Visuals:**<br>
The dashboard includes a wide range of visuals, including, among many others: 100% stacked column chart, decomposition tree, funnel, scatter chart with clusters, dynamic textboxes, and slicers



The dashboard uses good practices (incl. creating a separate table to store DAX measures, adjusting the names for specific visuals, using multiple pages to present data in a clear way, implementing a wide range of visuals and colors). 



**Dataset source:** https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting , own dataset
**Cover image source:** https://pixabay.com/pl/photos/zbiory-handlowy-monitor-biznes-1863880/

