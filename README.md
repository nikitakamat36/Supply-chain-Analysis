# Supply Chain Risk & Demand Optimization Analysis
A retail analytics project focused on identifying revenue leakage due to stockouts, seasonality, and poor inventory management. This project merges SQL queries with Power BI for data visualization to detect risk factors and improve inventory distribution.

**Problem Statement:**
Retail companies frequently face revenue loss because of:

1. Repeated stockouts of items in demand
2. Ineffective demand prediction
3. Poor inventory distribution among regions
4. Minimal impact of campaigns/ promotions 
5. Seasonal variations in demand

**The business wished to know:**

1. Which products or categories generate the maximum revenue
2. Which products face the maximum risk for stockouts
3. How stockouts influence sales performance
4. Whether marketing efforts significantly increase demand
5. How changes in operations might reduce revenue loss

**Business objective**
1. Evaluate sales and inventory efficiency
2. Identify products that have frequent stockout situations
3. Measure the effect of inventory stockouts on the company
4. Enhance inventory management and seasonal forecasting

**Technology used**

1.SQL (Data Analysis) Data extraction, KPI analysis, business queries

2.Power BI (Dashboard & Visualization)

3.Excel (Data Cleaning)

**Dataset**
Retail & supply chain transactional dataset (Walmart-style dataset from Kaggle)
5000+ transactions

**Key Business KPI's**

1. Total Revenue: ₹15M

2. Total Transactions: 5000

3. Average Order Value: ₹3052

4. Stockout Rate: ~52%

5. Total Quantity Sold : 15k

**Analysis**

**1. Sales Performance analysis**
* Revenue trend by month
* Product-wise sales performance contribution
* Category performance
* Store-wise revenue performance
* Customer purchase behavior
  
**Key findings**
- The electronics category accounted for about 52% of the total revenue, thereby outperforming all other categories
- TV and Tablets products recorded the highest sales revenue
- Sales were highest during the month of August
- Female customers and loyal customers segments generated the highest revenue

**2. Inventory & stockout Analysis**
* Frequency of product out-of-stock occurrences
* Risk of inventory at store levels
* Demand trend during stock-out occurrences
* Revenue implication of stock-outs

**Key findings**
- Total stockout percentage stood at 51.86%, demonstrating significant inefficiency in inventory planning
- Tablets, Fridges, and Smartphones displayed the most common occurrence of stockouts
- In high-demand items, stockouts were experienced during peak demand periods
- The average demand during stockout was more than 300 units

**3. Promotion impact analysis**
* Revenue earned from promotions
* Type of promotion performance
* Effects of discount on demand for sales

**Key findings**
- Promotions had some effects on total revenue, but not very significant
- Percentages and BOGO promotions did not have much impact on increasing demand
- Availability of product was a more important factor to earn revenue than any discounts

**Root Cause Analysis**
* High stockout frequency - Impacted the sales and customer dissatisfaction
* Poor seasonal demand planning - Caused inventory shortages during peak demand
* Moderate promotion effectiveness - caused inability to drive sales

**Business Impact**
High-demand electronic items experienced frequent out-of-stock situations during peak periods, that caused considerable revenue loss.

**Recommendations**
- Implement demand forecasting this will help with the stock out situations by reducing shortages during peak demand and will also help with better inventory planning
- Increase Safety Stock for High-Risk Products
- Optimize Inventory Allocation by Region
- Improve Promotion Strategy

**Dashboard Features**
1. Revenue KPIs
2. Monthly sales trends
3. Product-wise revenue analysis
4. Category performance tracking
5. Promotion effectiveness analysis
6. Inventory risk visualization
7. Store-level geographic analysis
8. Customer segmentation insights

**SQL Analysis**
1. Revenue aggregation
2. Monthly trend analysis
3. Product ranking
4. Stockout rate calculation
5. Revenue contribution analysis
6. Customer segmentation
7. Promotion effectiveness evaluation
8. Store-level performance analysis

