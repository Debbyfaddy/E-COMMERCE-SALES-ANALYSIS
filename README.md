<img width="1272" height="583" alt="1" src="https://github.com/user-attachments/assets/9f96d871-174b-4995-b9e0-a1141929e4d4" />

# E-COMMERCE-SALES-ANALYSIS
This project analyzes transactional data from the E-commerce industry, focusing on understanding sales performance, customer behavior, and regional trends. The dataset represents a synthetic retail environment where each transaction captures key details such as product categories, geographic regions, discounts, and purchase activity.

STORY OF DATA

The dataset originates from transactions in a synthetic retail store. Every time a customer makes a purchase (online or in-store), the system generates records that capture product details, customer identifiers, regions, discounts, and purchase information.

DATA SPLITTING AND PRE PROCESSING

-Purpose

This stage focuses on preparing the dataset for accurate and reliable analysis. Proper preprocessing ensures that inconsistencies, errors, and missing information do not distort insights. By structuring the data correctly, the analysis becomes more meaningful and supports better decision-making.

-Data Cleaning

To maintain data quality, several cleaning steps were applied:

Duplicate records were identified using Transaction ID and removed to avoid double counting revenue.
Inconsistent entries (such as mismatched category names or region labels) were standardized to ensure uniformity.
Data type corrections were performed (e.g., converting revenue and units sold into numeric format, and transaction date into date format).
Outliers in revenue and unit sales were reviewed to ensure they reflected valid transactions and not data entry errors.

-Data Splitting

The dataset was logically divided into:

Independent Variables (Inputs): Customer ID, Product ID, Region, Category, Transaction ID
Dependent Variables (Outputs): Revenue, Units Sold, Discount Applied, Clicks, Transaction Date

This separation allows analysis of how different factors (independent variables) influence key business outcomes like revenue and sales performance (dependent variables).

-Industry Context

The dataset belongs to the E-commerce industry, which involves online and retail transactions across multiple regions and product categories. This industry is highly data-driven, where understanding customer behavior, pricing strategies, and demand patterns is essential for competitiveness and growth.

-Stakeholders

Executives and finance department as the stake holders are to understand company revenue trends, profitability, and growth areas and to ensure accurate revenue reporting, pricing strategies, and margin calculations.
Value to the Industry

-This analysis provides significant value by:

Identifying high performing products, customers, and regions
Helping businesses optimize pricing and discount strategies
Revealing customer purchasing behavior and trends
Supporting data-driven decision-making to improve revenue and efficiency
Enabling companies to scale operations strategically across regions

PRE- ANALYSIS

POTENTIAL QUESTIONS

1. Which customers generated the highest revenue?
2. Which products generate the highest revenue overall?
3. Which regions generate the most revenue?
4. What is the impact of discounting on sales across different regions?
5. Do click-throughs translate into higher revenue in some regions than others?


EXPECTED INSIGTH
1. Identify customer segments or individuals with high revenue potential.
2.. top-revenue-generating products and categories.
3. Identify top-revenue-generating regions and potential areas for growth.
3. Finetune  top-revenue-generating regions and potential areas for growth.
4. Analyse regions where discounting has a significant impact on sales and those where it may not be effective.
5.  Identify regions where click-throughs are more likely to convert to revenue.


IN ANALYSIS

-Sales by Category

Observations:

Sales across categories are fairly balanced, with no category dominating significantly. Electronics generates the highest revenue at $11.33M, followed closely by Books and Toys, which are almost equal at around $11.2M. Clothing records slightly lower sales at $11.03M but remains competitive, while Home Appliances is the lowest at $10.56M, only about 7% behind Electronics.

Insights:

The small differences in revenue indicate strong competition across all categories. Clothing shows consistent demand despite ranking fourth. Home Appliances, although not far behind, may require improved pricing, promotions, or marketing strategies to boost performance.

-Sales by Region

Observations:

Sales performance across regions is nearly identical, with only a 0.17% difference between the highest and lowest regions. Each region contributes almost equally, showing no clear leader.
Insights:
This reflects strong geographic diversification, reducing reliance on any single market. Since all regions perform similarly, growth opportunities exist in every region, especially through localized marketing and product strategies.

-Top 5 Customers

Observations:

The top customer contributes about $12,021, with the remaining top five customers close in value, showing only about a $1,387 difference. These customers have similar spending patterns and contribute significantly to overall revenue.

Insights:

Retaining these high-value customers is critical, as losing even one could impact revenue. They are ideal candidates for personalized offers, loyalty programs, and upselling strategies. Their behavior can also be used as a benchmark to grow mid-tier customers.

-Transactions by Amount

Observations:

Most transactions fall within the 0–1000 range, accounting for the majority of purchases. The number drops significantly in the 1000–2000 range and becomes extremely low for transactions above 2000.

Insights:

Encouraging customers to move from low-value to mid-value purchases could significantly increase revenue. High-value customers, though few, should be retained through targeted strategies. The heavy reliance on low-value transactions poses a risk if transaction volume declines.

-Sales Trend

Observations:

Revenue peaks in November at around $4.83M, with October and December also showing strong performance. February records the lowest revenue at approximately $4.31M. Overall, there is a clear increase in sales during the year-end period.

Insights:

The higher sales in October to December reflect seasonal demand driven by holidays and promotions. February represents a weak period and offers an opportunity for targeted campaigns. Increasing focus on off-peak months and maximizing high-performing months can further improve overall revenue.

GENERAL OBSERVATION

Across all regions, revenue is almost evenly distributed, with Asia (33.43%, ~$18.50M), North America (33.30%, ~$18.41M), and Europe (33.26%, ~$18.38M) contributing nearly equal shares. This indicates a highly balanced and well-diversified global market with no strong regional dependency.

Across all regions, Electronics consistently leads sales (around $3.7M–$3.8M), followed closely by Books and Toys. Clothing performs slightly lower but remains strong, while Home Appliances is the weakest category in each region. However, the difference is small, showing that demand is fairly balanced across all product categories.

Customer contribution patterns show that revenue is not dependent on a few high-value customers. Even the top customers contribute only a small share of total revenue, especially in Europe and North America, indicating a broad and stable customer base.

Transaction behavior highlights that most purchases fall under $1000, with very few transactions above $2000. This confirms that the business is driven by high-volume, low-value purchases rather than high-ticket sales.
Seasonal trends are consistent across regions, with sales peaking in mid-year (May–June) and during the year-end period (October–December). November and December perform the strongest due to holiday demand, while February is the weakest month, reflecting a post-holiday slowdown.

RECOMMENDATION

Electronics remain the leading category in Asia, contributing $3,785,221.48, and efforts should focus on scaling premium products and creating bundle packages to further expand market share.
Home Appliances, which generated $3,526,166.71, require revival through targeted promotions, easy financing options, and strong after-sales services to increase competitiveness. Also, high-value customers, each contributing more than $12,000, should be retained by introducing VIP loyalty programs and exclusive offers that encourage long-term engagement.
Since 83,755 transactions fall below $1,000, volume-based strategies such as bundle deals and discounts can be used to maximize returns from this large segment of small purchases.
Seasonal optimization is also critical, as peak sales occur in May, June, and December; campaigns, inventory, and promotions should be aligned with these high-demand periods.
Finally, mid-year declines in July and August must be addressed by launching special events and targeted sales campaigns to maintain momentum and stabilize performance.


Books and Toys, generating approximately $3,720,000 each, are highly competitive with Electronics at $3,770,000. Cross-category promotions should be prioritized to boost sales across all three strong-performing categories.
Home Appliances, with revenue of $3,515,942.70, are noticeably lagging. Strategic local partnerships and targeted seasonal appliance deals can help close this performance gap.
Customer loyalty remains strong, with individual customers spending above $10,000 each. To deepen engagement, tiered incentives such as spend-based rewards and business account programs should be introduced.
As October  and November outperformed all other months. Holiday readiness, logistics, and campaigns should be ramped up well in advance to maximize this peak.
While March delivered a strong $4,705,422, sales softened in the following months. Spring-focused promotions can help sustain early-year momentum and counter seasonal dips.


Electronics ($3,774,579.99), Books ($3,731,770.63), and Toys ($3,731,614.45) generate almost equal revenue. To sustain this balance, category bundles and cross-selling campaigns should be promoted.
Home Appliances, at $3,516,292.49, continue to underperform. Growth can be supported through financing options, bundling with Electronics or Clothing, and launching seasonal appliance promotions.
Top customers in this region contribute only between $4,200 and $5,300, which is significantly lower than in Asia and Europe. Rather than relying on a few accounts, efforts should focus on expanding the customer base to increase overall revenue breadth.
Most transactions remain under $1,000, mirroring the global trend. Subscription plans, loyalty discounts, and repeat-purchase incentives would help maximize value from this large transaction volume.
Sales trends peak in May, June, and December. Targeted holiday and summer promotional campaigns can strengthen performance during these periods.
However, July and August show notable declines. Back-to-school campaigns and targeted discounts should be leveraged to stabilize mid-year performance and reduce revenue dips.

CONCLUSION

The analysis shows a balanced and globally diversified e-commerce business, with similar revenue contributions across Asia, Europe, and North America. Electronics, Books, and Toys lead performance, while Home Appliances presents an opportunity for improvement.

Sales are driven by high volume, low value transactions, indicating strong reach but a need to increase average order value. Seasonal trends highlight peak performance in May, June, and Q4, with dips in February and mid year.

Overall, future growth depends on improving weaker categories, increasing transaction value, leveraging peak seasons, and strengthening customer retention and engagement strategies.
