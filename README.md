# Comprehensive Performance Analysis of an Online Retail Store
Exploring global sales and profit trends alongside customer and product insights...

## Project Description
This project presents an in-depth analysis of an online retail store’s operations, focusing on key performance metrics including revenue generation, customer behavior, product performance, geographic distribution, sales trends, pricing, and profitability. By examining total revenue, average order value, top-selling and most profitable products, customer retention rates, and country-specific performance, the study identifies core drivers of business success and areas for improvement. The analysis also explores monthly and hourly sales patterns, pricing inconsistencies, and the relationship between price and sales volume, providing actionable insights to optimize marketing strategies, inventory management, and customer engagement. Overall, the project offers a holistic view of the store’s performance and serves as a strategic tool for informed decision-making.

## Data Sources
The primary dataset used for the analytics is the "Online retail" from Coursera project network.

## Tools Used
- Microsoft excel was used for Data cleaning
- Python (Jupyter notebook) was used for the analysis
- Tableau was used for the Visualization

## Data Cleaning and Preparation
- I separated invoice date from invoice time by editing the custom through format cells.
- 5,268 duplicated values were found and removed.
- 53,6641 unique values remain.

## Project Objectives
- Describe data to answer key questions to uncover insights
- Gain valuable insights that will help improve online retail performance
- Provide analytic insights and data-driven recommendations

## Result and Findings 
## Total Revenue
The online store generated a total revenue of $9,726,006.95, indicating a strong overall sales performance. This figure reflects the cumulative income from all transactions recorded during the whole period.

## Best-Selling Product Insight
The best-selling product is "WORLD WAR 2 GLIDERS ASSTD DESIGNS", with a total of 53,751 units sold. This product's exceptionally high sales volume indicates strong customer demand and possibly an effective marketing or pricing strategy behind it.

## Least-Selling Product Insight
The least-selling product is labeled "printing smudges/thrown away" with a total quantity of -19,200 units sold. The negative sales quantity likely indicates product returns, write-offs, or inventory adjustments rather than actual sales.

## Average Order Value (AOV) Insight
The Average Order Value (AOV) per invoice is $375.52, representing the average amount spent by customers per transaction on the online store. An AOV of $375.52 indicates that customers typically make medium-to-high-value purchases, suggesting either bulk buying or the presence of high-priced items in the catalog.

## Customer Base Insight
The online store recorded a total of 4,372 unique customers during the analysis period. Having 4,372 distinct customers indicates a moderate and active customer base, showing the brand's ability to attract and retain a diverse range of buyers.
When compared with total revenue ($9.73M), this suggests that each customer generated an average of about $2,225 in revenue, reflecting a high customer lifetime value (CLV) or frequent repeat purchases.

## Customer Spending Insight
The average spending per customer is $1,893.53, indicating the average total revenue generated from each unique customer during the analysis period. An average spend of $1,893.53 per customer demonstrates a high customer value, suggesting that the store attracts loyal and high-spending buyers.

## Top 5 Revenue-Generating Products Insight
These five products collectively generate a significant share of total store revenue, reflecting their strong market demand and customer preference. DOTCOM POSTAGE, the top performer, may represent shipping fees or digital order-related charges, making it a consistent and reliable revenue stream. The REGENCY CAKESTAND 3 TIER stands out as the top physical product, suggesting strong demand in the home décor or event accessories segment.

## Geographic Revenue Insight
The United Kingdom is the primary market driver, contributing the vast majority of total sales revenue. This dominance suggests that the business has a strong local presence, brand recognition, and an established customer base within the UK.
The high UK revenue share may also reflect factors such as optimized logistics, favorable pricing, or targeted marketing strategies within the domestic market.
In contrast, Saudi Arabia's minimal revenue ($131.17) highlights limited market penetration in that region, potentially due to low brand awareness, logistical constraints, or regional market differences.

## Monthly Sales Trend Insight
The sales trend shows fluctuations over the five-month period, with December 2010 recording the highest revenue ($746,723.61) and April 2011 the lowest ($492,367.84). The spike in December is likely linked to holiday season sales, reflecting increased consumer spending during festive periods.
The subsequent decline in early 2011 (January–April) suggests a post-holiday dip, which is typical in retail as customers reduce discretionary spending after the holiday rush. A rebound in March 2011 ($682,013.98) indicates potential seasonal promotions or restocking behavior, possibly due to spring events or product launches.

## Customer Retention Insight
With a customer retention rate of 69.97%, the online store demonstrates a strong level of customer loyalty and satisfaction. Nearly 7 out of every 10 customers made repeat purchases, highlighting effective customer engagement and post-purchase experience. The 3,059 repeat customers form a valuable core audience contributing significantly to revenue stability and reducing dependency on new customer acquisition.

## Top Customers by Purchase Frequency Insight
These customers represent the most engaged and loyal buyers, making multiple purchases and contributing consistently to revenue. The top customer (ID 14911) placed 248 orders, indicating extremely high engagement and possibly a wholesale or repeat individual buyer. The frequency data helps identify high-value, high-frequency customers, which is crucial for personalized marketing, loyalty programs, and VIP offers.

## Top Countries by Active Customers Insight
The United Kingdom dominates with 3,950 active customers, forming the core of the customer base and explaining its strong contribution to overall revenue. Other European countries have very small customer counts, indicating limited market penetration outside the UK.
The steep drop-off from the UK to Germany (95 customers) suggests a highly concentrated market, emphasizing the importance of UK-focused marketing and logistics.

##Hourly Sales Trend Insight
Peak sales hours occur between 10 AM and 3 PM, with the highest at 12 PM ($1,357,595.12), indicating that customers are most active during the midday period. Early morning hours (6–7 AM) show minimal activity, and the negative value at 6 AM likely reflects returns, cancellations, or data adjustments rather than actual negative sales.
Evening hours (6–8 PM) have significantly lower sales, suggesting that customer purchasing behavior is concentrated during the day, possibly due to work schedules or shopping patterns. This hourly trend can guide staffing, marketing campaigns, and real-time promotions to maximize revenue during high-traffic hours.

## Top 10 Most Profitable Products Insight
The most profitable products largely overlap with the top-selling items, indicating that high demand correlates with high revenue for these SKUs.
DOTCOM POSTAGE leads profitability, likely due to consistent sales and relatively low overhead costs. Decorative and gift-oriented items (like cake stands, T-light holders, party buntings, and night lights) dominate the list, highlighting the store's strength in lifestyle and festive merchandise.
Even mid-tier products (like RABBIT NIGHT LIGHT and PAPER CHAIN KIT) contribute significantly, suggesting that variety and seasonal products play a key role in overall profitability. Focusing on these high-performing products for marketing campaigns, cross-selling, and inventory optimization can maximize revenue and profit margins.

## Average Unit Price by Product (Top 5)
AMAZON FEE has the highest average unit price, likely representing service or transactional fees rather than a physical product. Physical products like Picnic Basket Wicker, CRUK Commission, and Manual show moderately high unit prices, indicating premium items or specialty goods. DOTCOM POSTAGE, despite being top-selling and profitable, has a relatively lower average unit price, suggesting high volume-driven revenue rather than margin-per-unit.

## Average Unit Price by Country (Top 5)
Customers in Singapore and Hong Kong purchase products at a higher average unit price, suggesting either premium products, higher shipping costs, or smaller, high-value orders. In contrast, countries like Portugal, Cyprus, and Canada show low average unit prices, which could indicate bulk, low-cost items, or limited engagement with premium products.

## Pricing Inconsistencies Insight
A total of 3,442 products have inconsistent unit prices, indicating potential data entry errors, varied supplier costs, or promotional pricing differences. Products like SET 2 TEA TOWELS I LOVE LONDON with 11 different unit prices suggest either frequent discounting or lack of standardized pricing. Pricing inconsistencies can confuse customers, distort revenue calculations, and impact inventory valuation.

## Price vs. Sales Volume. 
Correlation coefficient: -0.0085
This indicates a very weak negative relationship between price and sales volume. The negative correlation suggests that higher prices are slightly associated with lower sales volume, but the relationship is almost negligible given the value is close to 0.
This implies that price changes do not strongly impact the quantity sold for most products.

## Country Customer & Invoice Insight:
The United Kingdom dominates both customer count and transaction volume, highlighting it as the core market for the online store. With 3,950 active customers generating 23,494 invoices, the UK demonstrates high customer engagement and repeat purchase behavior, aligning with the previously reported 69.97% retention rate.

## Top Countries by Customer Count and Invoice Volume
The United Kingdom dominates both customer base and invoice volume, confirming it as the store's primary and most active market. The high invoice count relative to customers in the UK suggests strong repeat purchase behavior and high engagement per customer, contributing significantly to overall revenue.
Germany, France, and Belgium rank consistently in both metrics, indicating moderate international presence, while countries like EIRE appear in invoices but not customers, suggesting possible data inconsistencies or shared customer accounts. The steep drop from the UK to other countries highlights market concentration, emphasizing the need for focused UK strategies while exploring growth opportunities in underrepresented regions.

## Conclusion
The online store demonstrates a strong overall performance, with a total revenue of $9,726,006.95, driven primarily by the United Kingdom, which contributes the majority of customers, invoices, and revenue. The average order value ($375.52) and average spending per customer ($1,893.53) indicate a healthy customer base with high engagement and repeat purchases, supported by a retention rate of 69.97%.
Top-performing products such as DOTCOM POSTAGE and REGENCY CAKESTAND 3 TIER drive both sales volume and profitability, while some products show pricing inconsistencies, which may affect revenue accuracy. The monthly and hourly sales trends reveal clear seasonal and daily peaks, allowing the store to optimize inventory and marketing efforts. Geographic analysis highlights high market concentration in the UK with potential for expansion in Europe and other international markets.
The correlation between price and sales volume is very weakly negative (-0.0085), suggesting that price changes have minimal impact on sales, and revenue is more influenced by product demand, marketing, and promotions.

## Recommendations
- Focus on High-Performing Products
Prioritize top-selling and most profitable products for promotions, bundling, and inventory optimization to maximize revenue and profit margins.

- Address Pricing Inconsistencies
Standardize unit prices across products and channels to improve data accuracy, maintain customer trust, and optimize revenue reporting.

- Enhance Customer Retention Strategies
Introduce loyalty programs, personalized offers, and exclusive discounts to retain high-value customers and encourage repeat purchases.

- Optimize Marketing and Promotions by Time and Region
Target peak hours (10 AM–3 PM) and high-sales months with campaigns. Expand marketing in underrepresented regions like Germany, France, and Belgium to diversify the revenue base.

- Leverage Data for Strategic Decisions
Monitor top customers and their purchase behavior to design VIP programs. Use insights from average unit prices and sales volume correlations to inform pricing strategies and promotional efforts.

## Limitations
- Data Completeness and Quality
Some entries in the dataset contain negative sales values, pricing inconsistencies, or missing information, which may affect the accuracy of revenue and product-level analysis.

- Limited Historical Context
The analysis covers a specific time period and may not fully capture long-term trends or seasonal fluctuations outside the dataset timeframe.

- Customer Information Constraints
Insights about customers are limited to IDs and transaction counts, with no demographic or behavioral data, restricting deeper analysis on customer segmentation or preferences.

- Geographic Scope
While revenue and customer data exist for multiple countries, the majority of sales are from the UK, which may skew global market insights.

- Pricing and Discount Effects
The dataset lacks detailed information on promotions, discounts, and shipping costs, which can influence AOV, unit price, and sales volume correlations.

  
