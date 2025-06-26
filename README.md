# ALPHA-SUPERMARKET-SALES-ANALYSIS-REPORT-2024


INTRODUCTION

Objective of the Project

The project objective is to develop an integrated business intelligence system for Alpha Supermarket to monitor and optimize retail performance across multiple dimensions.

Problem Being Addressed

The problem being addressed is lack of centralized visibility and data-driven insights in Alpha Supermarket’s operations.

The supermarket was likely struggling with fragmented business intelligence — unable to easily track which cities, payment methods, product categories, and time periods were driving the most revenue and volume. Without integrated analytics, management couldn’t identify top-performing locations (Alexandria), optimal payment strategies (cash preference), or seasonal sales patterns.

Key Datasets

Based on the Alpha Supermarket dashboard, the key datasets used include:

Sales Transaction Data — Core dataset containing individual sale records with transaction amounts, quantities, timestamps, and payment methods across cash, credit card, and eWallet options.

Product Catalog Data — Product information including categories (Electronics, Food, Home & Garden, Sports, Books, Toys), brand classifications, and product types for categorization analysis.

Geographic/Location Data — Store or customer location data covering multiple cities including Alexandria, Cairo, and Ismailia to enable geographic performance analysis.

Customer Payment Data — Payment method preferences and transaction values across different payment types to track revenue distribution patterns.

Temporal/Date Data — Time-series sales data spanning multiple years to track seasonal patterns, daily fluctuations, and trend analysis shown in the time-based charts.

Brand/Vendor Data — Brand performance metrics distinguishing between different brands, with brand categorization for market share analysis and competitive positioning.

These datasets are integrated to provide a comprehensive view of supermarket operations, enabling cross-dimensional analysis of sales performance, customer behavior, and business trends across locations, time periods, and product categories.

STORY OF DATA

The data tells the story of Alpha Supermarket’s retail operations flowing from individual customer transactions through product categories, payment methods, geographic locations, and time periods to create a comprehensive view of business performance across multiple operational dimensions.
Data Source: The data was obtained from Kaggle.com

Data Collection Process: This data was obtained from Kaggle.com

Data Structure: The data contains 1,000 rows with each representing a distinct transaction and 14 columns representing invoice ID, branch, city, customer type, gender, type, unit price, quantity, date, time, payment, cost, gross income, and rating.

Data Limitations or Biases

Incomplete Customer Journey — Only captures in-store transactions, missing online purchases, competitor visits, and customer research behavior outside the store
Limited Temporal Coverage — Historical data may have gaps or inconsistent collection periods
Product Classification Inconsistencies — Manual categorization of products may lead to misclassification between different categories
Geographic Sampling Constraints — Data from limited cities may not represent broader market conditions
Inherent Biases:

Payment Method Selection Bias — Payment preferences may reflect demographic or infrastructure factors rather than true customer choice
Store Location Bias — Performance differences may be influenced by store size, location quality, or local demographics
Survivorship Bias — Only successful transactions are captured, missing abandoned carts or failed payment attempts
Seasonal Collection Bias — Data collection periods may not represent normal business cycles or seasonal variations
Technical Limitations:

Data Integration Challenges — Potential inconsistencies when combining data from multiple sources and systems
Real-time Accuracy — Delays between transaction occurrence and dashboard updates
Missing External Factors — Economic conditions, competitor activities, and market trends not captured in internal data
DATA SPLITTING AND PREPROCESSING

Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. Thereafter, the data was converted to a standard excel table to ease analysis.

To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”.

To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to “Go to Special” and select “Blanks”, finally click on OK.

Handling Missing Values: There are no missing values in the data.

Data Transformations: No data transformations were performed.

Tool used: Power BI

DATA SPLITING

Dependent Variable(s)

gross income

rating

Independent Variables

invoice ID — Unique ID (identifier only, not analytical

branch — Store location (A, B, C)

city — City of the store

cust_type — Customer category (e.g., Member or Normal)

gender — Gender of the customer

type — Product line/category

unit_price — Price per item

quantity — Items sold per transaction

date — Date of sale

time — Time of transaction

payment — Payment method used

cost — Operational cost or total amount before profit

Industry Type

Retail / FMCG (Fast Moving Consumer Goods)

Specific focus on Supermarkets and Retail Chain Operations

Stakeholders for the project

Store Managers — Monitor performance, manage staffing,optimize stock

Marketing Team — Understand customer preferences and trends

Sales Executives — Track revenue, identify best-performing products/branches

Operations Team — Optimize resource allocation, track peak hours

Executives & Investors — Make strategic decisions for expansion, investments, and ROI

Customer Service Teams — Improve satisfaction based on ratings and feedback trends

What Success Means in This Industry

Increased Gross Income per transaction/store

High Product Turnover (quantity sold)

Consistently High Customer Ratings

Efficient Payment Processing (digital adoption)

Balanced Sales Across Branches & Cities

Data-Driven Inventory and Staff Management

PRE-ANALYSIS

Potential Analysis Questions

Which branch or city generates the most profit?

What product types drive the highest revenue and customer satisfaction?

Are there gender-based differences in purchasing behavior?

What is the impact of payment method on gross income?

Do customer types (Member vs. Normal) spend differently?

Which time slots or days of the week have the highest sales?

Is there a correlation between unit price and quantity sold?

Which product categories receive better ratings?

Potential Insights & Outcomes

Identification of high-performing branches or products

Discovery of underperforming categories needing promotion or pricing change

Insight into customer demographics and preferences

Analysis of peak business hours to optimize operations

Patterns in payment behavior that can guide policy (e.g., cashless incentives)

Understanding the relationship between sales and customer satisfaction

IN-ANALYSIS

IN ANALYSIS OBSERVATIONS AND INSIGHTS

IN ANALYSIS INSIGHTS

Total Quantity Sold: 5,510 items

Top Performing Branch: Branch A

Top City by Sales: Alexandria (5.27K gross income)

Best Payment Type: Cash

Top Product Type (by Quantity): Electronic accessories (971 items)

Top Product Brand (by Performance): Elect

Branch & City Performance

Branch

A is the top performer in gross income and quantity. All three branches (A, B, C) show very close performance (around 5.06K–5.27K gross income), indicating strong operational consistency.

Alexandria slightly edges out other cities, suggesting market concentration or

better customer engagement.

Payment Insights

Cash is the most preferred payment method, followed closely by e Wallets,

with credit card usage slightly lower.

Marketing campaigns can be tailored to promote loyalty programs through

eWallets or encourage digital payments with incentives.

Product Analysis

Electronic accessories lead in quantity sold, followed by: Food and beverages, Sports and travel, Fashion accessories, Home and lifestyle, Health and beauty (lowest, 854 items)

Diversified demand indicates a wide product appeal, with possible focus on

bundling underperforming products.

Time-Based Trends

The gross income by date shows: A positive trend with recurring spikes, promotional periods or seasonal effects.

Opportunity to optimize campaign timing to maximize these peaks

DATA VISUALIZATIONS & CHARTS

GROSS INCOME BY PAYMENT


![image](https://github.com/user-attachments/assets/58e3115c-b261-41c9-90eb-c8dbb980c977)

This bar chart displays gross income distribution across three payment methods:

Cash generates the highest revenue at $5.3k, eWallet follows at $2.6k, and Credit card contributes $4.8k. The total gross income across all payment methods is $12.7k.

The data shows cash transactions dominate the payment mix, representing approximately 42% of total income, while credit cards account for 38% and eWallets make up 20%. This suggests a business with diverse payment acceptance but strong cash transaction volume.

GROSS INCOME BY BRANCH

![image](https://github.com/user-attachments/assets/20bb0037-a4dc-490a-8175-05f0769e026b)


This branch performance analysis shows a highly concentrated revenue distribution with Branch A generating $5.06k (32.86%) of total gross income, significantly outperforming the other branches. Branch B contributes $5.27k (34.24%) while Branch C accounts for $5.06k (32.86%).

The data reveals Branch B actually leads with the highest revenue at $5.27k, followed by Branches A and C which are nearly tied at $5.06k each. This relatively balanced distribution across the three branches, with each contributing approximately one-third of total revenue, suggests a well-distributed business model rather than over-reliance on a single location. The small performance gaps between branches indicate consistent operational standards across the network.

GROSS INCOME BY CITY

![image](https://github.com/user-attachments/assets/a43a47c4-47bd-4bb8-9d08-9ec555055806)

This geographic performance analysis shows Alexandria leading with $5.27k in gross income, followed by Cairo and Ismailia each generating $5.06k. The revenue distribution is relatively balanced across the three cities, with Alexandria holding only a slight advantage of approximately $210k over the other two locations. This near-equal performance suggests consistent operational standards and similar market conditions across all three cities. The minimal variance indicates a well-managed multi-city operation with no significant underperforming locations, though Alexandria’s marginal lead may reflect slightly better market positioning or customer demographics in that location.

GROSS INCOME BY DATE

![image](https://github.com/user-attachments/assets/67cad396-2290-4b09-aab8-cfe5c1d3b49d)


This temporal sales analysis reveals highly volatile daily revenue patterns from January to March 2019, with gross income fluctuating between approximately $50 and $400. The data shows significant day-to-day variability with multiple peaks reaching $300–400 and several valleys dropping to $100 or lower. Notable patterns include periodic spikes suggesting possible weekly cycles, promotional periods, or seasonal shopping behaviors. The overall trend appears relatively stable without clear upward or downward momentum, indicating consistent but unpredictable daily performance. This volatility suggests the business experiences regular demand fluctuations that could be influenced by factors like weekends, paydays, marketing campaigns, or external market conditions requiring careful inventory and staffing management.

QUANTITY BY PRODUCT TYPE

![image](https://github.com/user-attachments/assets/29b56c30-6cbb-492b-9ec6-c13ff7e439e3)


This product category analysis shows relatively balanced inventory distribution across six categories, with quantities ranging from 654 to 971 units. Electronics leads with 971 units, followed closely by Food at 962 units and Sports at 920 units. Home & Garden (911), Books (902), and Toys (654) complete the range. The distribution suggests a diversified product portfolio catering to various customer needs, from essential items like food and electronics to recreational products like sports equipment and toys. Toys show the lowest inventory levels, which may indicate either lower demand, higher turnover, or strategic inventory management for this category. The relatively small variance between categories demonstrates balanced stock management across the product mix.

FINAL DASHBOARD

![image](https://github.com/user-attachments/assets/c25e1dc9-d0b1-4f41-ba10-8806404917ce)


The final dashboard highlights the combined correlations and relationship between the individual charts with the help of slicers.

OBSERVATIONS AND ACTIONABLE RECOMMENDATIONS

1. Sales Performance

Total Quantity Sold: 5,510 units across all product types.

Top

Branch: Branch A leads in total gross income and likely customer volume.

Top City: Alexandria contributes the highest gross income (5.27K), indicating

stronger market penetration or a loyal customer base.

Gross income is evenly distributed across all branches and cities, reflecting stable

business operations.

2. Product Line Performance

Electronic accessories are the top-selling product line, suggesting high customer demand and fast-moving stock.

Health and beauty products have the lowest quantity sold, indicating low visibility,

customer interest, or pricing challenges.

Product variety is well-balanced, though differences in customer preference are

evident.

3. Customer Payment Behavior

Cash remains the dominant payment method, showing customer preference for

traditional transactions.

EWallets are gaining traction and nearly match cash usage, suggesting growing digital

payment adoption.

Credit card use is relatively low, possibly due to demographic or infrastructure

factors.

4. Time-Based Sales Trends

Consistent sales spikes are seen in the gross income by date graph — likely tied to

weekends, promotions, or holidays.

Sales remain relatively stable across the 3-month period (Jan–Mar 2019), with no

sharp drops, indicating a loyal customer base and steady demand.

5. Customer and Branch Dynamics

Branch A’s success may be linked to staff efficiency, location, or operational

excellence.

Slight performance differences between branches and cities suggest operational equity,

but deeper analysis into store-level customer experience could uncover minor

inefficiencies.

ACTIONABLE RECOMMENDATIONS

Product & Sales Strategy

Promote Low-Performing Categories

Launch promotions or bundles for Health and Beauty to increase visibility and sales.

Use cross-selling with popular items like Electronics.

Targeted Product Campaigns

Focus on Electronic accessories as a flagship product — expand inventory or create

premium product lines.

Implement product-specific promotions during sales peaks (based on time series insights).

Payment & Customer Engagement

Encourage Digital Payments

Offer discounts or loyalty points for eWallet payments to reduce cash handling and

align with tech-savvy shoppers.

Consider partnership with digital payment platforms for marketing campaigns.

Understand Credit Card Aversion

Investigate customer resistance to credit cards — offer exclusive deals or educate on secure transactions.

Location-Based Strategies

Expand or Invest More in Alexandria

Enhance infrastructure, advertising, or staffing in Alexandria, the top-performing

city.

Use Alexandria as a benchmark branch for training and operational best practices.

Geo-Specific Promotions

Tailor offers by branch or city based on customer demographics and buying behavior.

REFERENCEE: The data for this project was obtained from Kaggle.com




