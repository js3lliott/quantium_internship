# Transaction Data Analysis for Chip Sales


## Introduction

This project aimed to analyze transaction data for chip sales in order to understand customer behavior and optimize store strategy. The data consisted of customer transaction records from a national grocery store chain over a 12-month period. This project was completed using Python and various libraries including Pandas, Matplotlib, and Scikit-learn.


## Insights and Recommendations

Based on the analysis conducted on the client's transaction data, we identified the top 3 sales-contributing segments as Older families (Budget), Young Single/Couples (Mainstream), and Retirees (Mainstream) with total sales of $156,864, $147,582, and $145,169, respectively. The following insights were found:

- Young Singles/Couples (Mainstream) have the highest population, followed by Retirees (Mainstream). This explains their high total sales.
- Despite Older Families not having the highest population, they have the highest frequency of purchases, which contributes to their high total sales.
- Older Families, followed by Young Families, have the highest average quantity of chips brought per purchase.
- The Mainstream category of "Young and Midage Singles/Couples" have the highest spending of chips per purchase. The difference to the non-Mainstream "Young and Midage Singles/Couples" are statistically significant.
- The chip brand "Kettle" is dominating almost every segment as the most purchased brand.
- The second most purchased brand, with a few exceptions, is "Smiths". The exceptions are "Doritos" being the second most purchased brand for "Young Singles/Couples" and "New Families - Mainstream", while Pringles is the second most purchased brand for "New Families - Premium".
- The most frequent chip bag size purchased is 175g followed by 150g for all segments.

Based on these findings, we recommend the following strategies for each segment:

- For Older Families, focus on the Budget segment. We can give promotions that encourage more frequent purchases, and we can run promotions that encourage them to buy a higher quantity of chips per purchase (e.g. a 3 for $10).
- For Young Singles/Couples, focus on the Mainstream segment. We can collaborate with Doritos merchants to do some branding promotion catered to "Young Singles/Couples - Mainstream" segment. Additionally, since this segment's strength is their population quantity, we should make sure our promotions reach them frequently.
- For Retirees, focus on the Mainstream segment as well. Since their population quantity is one of the main contributors to the high sales total, we should spend more effort on making sure our promotions reach as many of the population as possible and frequently.
- For general promotions, almost all segments had "Kettle" as the most frequently purchased brand and 175g chip bag size as the preferred bag size. Thus, we should take advantage of these top two insights and promote chips that fit these preferences.


## Data Cleaning & Exploration

We started by cleaning the data and then conducting exploratory data analysis to understand the purchasing behavior of customers. We identified the following:

- top-selling chip brands per customer segment
- the average price per unit
- total sales per customer segment


## Customer Segmentation

To better understand the customer segments, we performed a segmentation analysis by lifestage and customer type to group customers based on their purchasing behavior. The resulting segments were analyzed to understand their characteristics and preferences. The results showed that the top segments by total sales were mainstream young singles/couples, mainstream retirees, and budget older families. FFrom these insights, we made several recommendations for the store, including increasing promotion of the top-selling chip brands, introducing more premium chip brands to target the mainstream young singles/couples segment, and creating more appealing store layouts to increase sales of premium chip brands.


## Uplift Modeling

Uplift modeling was used to identify benchmark stores to test the impact of trial store layouts on customer sales. This involved predicting the uplift in sales that would result from changing the layout of a trial store. The results were used to make data-driven decisions on store layout changes.


## Conclusion


In conclusion, through our analysis of the transaction data, we were able to gain valuable insights into the customer behavior and preferences in relation to chip purchases. By identifying the top-selling customer segments, most popular chip brands and bag sizes, and other key purchasing trends, we can now make strategic business decisions to optimize store sales and profitability.

With our recommended focus on key segments and brands, as well as strategies to leverage their strengths in frequency of purchases and quantity purchased, we are confident that the store can maximize sales and customer loyalty. In addition, by focusing on the most popular brands and bag sizes, we can further increase sales by promoting these products more heavily.

Overall, this analysis showcases the power of data-driven decision making to improve store strategy and drive sales. We recommend ongoing analysis and monitoring of customer behavior and preferences to stay ahead of changing trends and remain competitive in the market.