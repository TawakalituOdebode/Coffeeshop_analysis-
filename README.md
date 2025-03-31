# Coffeeshop_analysis-
## PROJECT OVERVIEW:
This project explores coffee sales in three business locations to derive insights needed to make strategic business decisions.

## PROBLEM STATEMENT:
While the coffee shop makes regular daily sales, it is important to identify:

-The bestselling products across all categories.

-Peak transaction period 

-The monthly revenue trend to detect growth
  
## DATA SET:
**Data source**-Kaggle( Maven Analytics)
**Data Description**

### ** Coffee shop Analytics Data**
| Column Name             | Description                                                    |
|-------------------------|----------------------------------------------------------------|
| Transaction_ID (Primary Key) | A unique identifier for each product transaction.            |
| Transaction date        | Date when each transaction was made.                           |
| Transaction_Qty         | The number of products bought at the time of the transaction.  |
| Store_ID                | The unique identity for each store.                            |
| Store Location          | The location where the transaction was made.                   |
| Product_ID              | The unique product identity.                                   |
| Unit_price              | The price of each product.                                     |
| Product_category        | The category of each product.                                  |
| Product_type            | The type of product purchased.                                           |


## DATA ANALYSIS:
-Data cleaning  process using excel functions

-creating calculated columns- **revenue**, creating time of day column using the IF function

	=IF(HOUR(E3)<12, "Morning", IF(HOUR(E3)<18, "Afternoon", "Night"))
 
-Utilized Excel’s pivot table function to create KPI’s.

-Visualization and dashboard creation using excel charts.

## KEY INSIGHTS AND RECOMMENDATIONS:
**Revenue Generation**
-The total revenue generated stands at $699K, with 214K units sold.
-The average price per unit is $3.38, which aligns with premium coffee pricing in the market.

**Top-selling Product and Category**
-Barista Espresso is the top-selling product by revenue, generating $91,406.
-Coffee dominates the category section with revenue of $269,952, followed by Tea $196,406 and Bakery $82,316.

**Sales Trend**

-**Time of Day**: Most transactions occur in the morning 54.82%, followed by the afternoon 35.66% and night 9.52%. This could be attributed to the early work rush by customers.

-**Monthly Trend**: Revenue has been increasing steadily, from $81,678 in January to $166,486 in June, suggesting a growing customer base or seasonal demand.

-**Weekly Trend**: Sales peak on Monday $102K, and remain consistent midweek before dipping on Saturday $97K.

### RECOMMENDATIONS
**Optimize Sales Timing**

-**Leverage Afternoon Sales**: Launch targeted promotions or flash sales during the morning hours (which account for 54.82% of transactions) to drive even higher transaction volumes and capitalize on peak customer traffic.

-**Enhance Night-Time Engagement**: Introduce incentives such as discounts or exclusive menu items during the night (currently at 9.52% of transactions) to boost sales during this underutilized time slot.

**Product and Category Focus**

-**Promote High-Performing Products**: Create bundled offers or loyalty programs centered around top sellers like Barista Espresso, Brewed Chai Tea, and Hot Chocolate. This can help increase the average transaction value and encourage repeat purchases.

-**Cross-Sell Within Categories**: Implement in-store or online recommendations that pair complementary items, such as bakery products with coffee, to enhance overall revenue per customer and diversify product interest.

**Day-of-Week Strategy**

-**Capitalize on Monday's Sales Peak**: Launch special promotions or "Monday boost" campaigns, considering Monday sees the highest revenue at $102K. This can help sustain momentum at the start of the week and potentially smooth out midweek fluctuations.

**These recommendations will help refine the coffee shop’s business strategy, optimize operations, and ultimately drive more revenue through data-driven decisions.**

