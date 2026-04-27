# Back Ground and Overview
BazarNova — a leading Turkish retail chain with a strong global presence, known for its diverse product offerings and commitment to customer satisfaction.

The company has significant amount of data for 2017 on it's sales, and product offering that has been underutilized. This project thoroughly analyze and synthesizes this data in order to undercover critical insights that will improve BazarNova's commercial success.

Insight and recommendation are provided in the following key areas:
* Top Product & Category Insights: Identifying the highest-performing products and categories, analyzing their contribution to overall revenue and sales growth.
* Seasonal & Time-Based Trends: Exploring how sales fluctuate across different seasons, months, and time periods to uncover patterns and peak performance windows.
* Promotional Impact Analysis: Measuring the effectiveness of promotional campaigns and discounts on sales performance and customer behavior.
* Regional & Store Performance: Analyzing sales performance across different regions and store locations to identify strengths, weaknesses, and growth opportunities.

An interactive dashboard can be download [here](https://public.tableau.com/authoring/BazarNova_Project/Dashboard1#1)







# Data Structure Overview
BazarNova's database structure as seen below consists of 6 tables: sales, product_names, product_hierarchy, city_names, store_names, store_cities with a total row count of 18,108 records.

![Dashboard Preview](https://github.com/Thuwaybah99/BazarNova-retail-analysis/blob/81b1d06d3e739f361e2fad9085f96a961a97ebc0/photo_5985349201623190575_y.jpg)

Prior to beginning the analysis, a veriety of cleaning steps were condected and the finle file can be downloaded from [here](https://github.com/Thuwaybah99/BazarNova-retail-analysis/blob/34901fe5e6acc3059e5dfe1c2b8038c92c2ee753/Clean%20all%20in%20one.xls).








# Executive Summary
### Sales Trends:
![Dashboard Preview](https://github.com/Thuwaybah99/BazarNova-retail-analysis/blob/d0a9b5efcd78324128a6cdb6bffca7878e0f9078/Sales%20over%20time.jpg)
* Sales remained relatively stable and within an average of 480 sales during the early months (April–August).
* A gradual upward trend began from August, indicating improving performance.
* Sales continued to increase steadily through September, October, and November.
* A significant spike occurs in December, marking the highest sales point of the year 54% of total sales.
* The December surge represents an extreme increase (≈120%) compared to earlier months.
* This sharp rise suggests a strong seasonal effect, likely driven by end-of-year demand.
* Overall, the trend shows a shift from stable performance to accelerated growth in the final quarter.

An interactive dashboard representing sales trend over time can be found [here](https://public.tableau.com/authoring/BazarNova_Project/Salesovertime#1).


### Product Performance:
![Dashboard Preview](https://github.com/Thuwaybah99/BazarNova-retail-analysis/blob/80582731ccd3c27ccce97adeab46cbf95ffce4f8/1q.jpg)
* (H01) hierarchy scored 1,433 sales records that results in 50% of total revenue.
* (H00) Scored the highest in sales 72.6% a total of total sales.
* The top 3 products in sales where Nano Gril flow, Hand Held Milk Frother, and Power Dryer flow representing 9% of total revenue.

An interactive dashboard representing product performance can be found [here](https://public.tableau.com/authoring/BazarNova_Project/ProductsPerformance#1) and hierarchy performance [here](https://public.tableau.com/authoring/BazarNova_Project/TopHierchybyRevenue#1).




### Promotion impact:
![Dashboard Preview](https://github.com/Thuwaybah99/BazarNova-retail-analysis/blob/1479dd37055829e8406ee377250a52a22bfe6d83/aaaaaa.jpg)
* Promotion 14 was the top-performing campaign, significantly outperforming all other promotions with approximately 9,000 total sales that resulted in 57% of total revenue, making it the strongest driver of revenue in the dataset.
* Several promotions showed weak or minimal performance, particularly Promo 03, Promo 07, Promo 08, and Promo 09, indicating these campaigns may require review, redesign, or discontinuation.
* 85% of Promotion 14 sales came from Hierarchy H00, suggesting this segment responded exceptionally well to the campaign.
* Hierarchy H02 demonstrated consistently poor performance across most promotions, with little to no sales activity recorded. The only notable exception was Promotion 14, which generated 2.5% of sales within this hierarchy.
* Other hierarchies generally showed broader positive engagement across multiple promotions, indicating stronger responsiveness compared to H02.
* Promotion 16 sales were 100% concentrated in Hierarchy H01, suggesting this promotion had a highly specific appeal within that segment only.
  
An interactive dashboard representing the promotion impact can be found [here](https://public.tableau.com/authoring/BazarNova_Project/Promoperformance#1)






### Store Performance:
![Dashboard Preview](https://github.com/Thuwaybah99/BazarNova-retail-analysis/blob/c3cffb71567d1d8dd3403b0e04e28c0c61282f79/Store%20Performance.jpg)
* DIGI and Electro World (National) are the top-performing stores, showing 70% of total sales and 76% of total revenue compared to the other stores.
* Both stores demonstrate similar revenue levels, although DIGI slightly outperforms in total sales.
* The majority of revenue for both DIGI and Electro World (National) is driven by the H01 category, indicating it is the primary revenue contributor.
* In contrast, the H00 category dominates sales volume across these stores, suggesting high transaction frequency but potentially lower pricing.
* Overall, performance differences across stores suggest that product category mix plays a key role in driving both sales and revenue outcomes.

An interactive dashboard representing store performance can be found [here](https://public.tableau.com/authoring/BazarNova_Project/Storesperformance#1)




# Data Gabs
While the dataset provides a solid foundation for analysis, it is important to acknowledge certain limitations that may impact the completeness and generalizability of the findings.


Limited store coverage in the dataset: Although the company operates 144 stores, only 6 stores were included in this analysis. This means the findings may not fully represent overall business performance across all locations, and broader store data would improve the accuracy and reliability of insights.


# Recommendations
Based on the key insights derived from the analysis, the following recommendations are proposed to enhance sales performance, optimize promotional strategies, and support data-driven decision-making across the business.

* Leverage high-performing hierarchies: Focus on expanding and promoting products within H01 and H00, as they are the primary drivers of revenue and sales. Increasing inventory and visibility for these categories can further boost performance.

* Capitalize on seasonal demand: Since sales spike significantly in December, implement early promotional campaigns and stock planning starting from Q3 to maximize end-of-year revenue opportunities.

* Optimize promotional strategy: Replicate the success factors behind Promotion 14 across other campaigns, while reassessing or discontinuing underperforming promotions such as Promo 03, 07, 08, and 09.

* Target hierarchy-specific promotions: Tailor campaigns to specific product hierarchies, as seen with Promotion 16 (H01) and Promotion 14 (H00), to improve engagement and conversion rates.

* Improve underperforming categories: Investigate H02’s low performance by reviewing product relevance, pricing, or marketing efforts, and consider repositioning or reducing focus if performance does not improve.

* Enhance store-level strategies: Analyze and replicate the strategies of top-performing stores like DIGI and Electro World (National) across other locations to improve overall performance.

* Balance sales and revenue mix: Since high sales volume (H00) does not always translate to high revenue, focus on upselling higher-margin products (H01) to improve profitability.

* Expand data coverage: Incorporate data from all 144 stores to enable more accurate insights and better decision-making at a company-wide level.

