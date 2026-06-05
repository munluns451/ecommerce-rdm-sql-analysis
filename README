# E-Commerce RFM Customer Segmentation Analysis 🛒

## Project Overview
Advanced SQL analysis of 541,909 real e-commerce transactions using 
RFM (Recency, Frequency, Monetary) methodology to segment 4,372 customers 
into actionable business categories. Built using CTEs, subqueries and 
CASE WHEN scoring in SQLite.

## Data Source
Online Retail Transactions Dataset
Source: Kaggle — abhishekrp1517
Period: December 2010 to December 2011

## Tools Used
- SQL (SQLite)
- DB Browser for SQLite
- CTEs (Common Table Expressions)
- Subqueries
- CASE WHEN scoring

## What is RFM Analysis?
RFM stands for Recency, Frequency and Monetary value.
Every customer gets scored 1-5 on each dimension:

- Recency: How recently did they purchase? (1=long ago, 5=recently)
- Frequency: How many orders did they place? (1=once, 5=10+ orders)
- Monetary: How much did they spend? (1=under $100, 5=over $5000)

Total RFM score = Recency + Frequency + Monetary (max 15)

## Customer Segments & Key Findings

| Segment | Customers | Avg Spend | Avg Orders |
|---|---|---|---|
| Champion | 711 | $10,320 | 17 orders |
| Loyal Customer | 1,290 | $1,717 | 4 orders |
| Potential Loyal | 1,422 | $589 | 1.7 orders |
| At Risk | 603 | $312 | 1.2 orders |
| Lost | 313 | $207 | 1 order |

## Key Business Insights
1. 711 Champion customers spend $10,320 on average — protect these VIPs
2. 1,422 Potential Loyal customers are the biggest opportunity group
3. 603 At Risk customers need urgent win-back campaigns
4. 313 Lost customers bought once and never returned

## Business Recommendations

1. Protect Champions
   711 customers averaging $10,320 each drive massive revenue.
   Offer VIP loyalty programs, early access to new products
   and personalised service to retain them.

2. Convert Potential Loyal customers
   1,422 customers with avg 1.7 orders are one purchase away
   from becoming loyal. Send targeted discount offers and
   personalised product recommendations immediately.

3. Win back At Risk customers
   603 customers are slipping away. Launch urgent email campaign
   with 20% discount and free shipping to re-engage them before
   they become lost permanently.

4. Analyse Champion buying patterns
   Study what Champions buy and when — use this to recommend
   similar products to Potential Loyal customers to accelerate
   their journey to loyalty.

5. Accept and learn from Lost customers
   313 Lost customers bought once and never returned. Survey them
   to understand why — pricing, product quality or delivery issues
   — and fix the root cause.

## SQL Concepts Used
- CTEs (Common Table Expressions) — WITH ... AS
- Subqueries inside FROM clause
- CASE WHEN scoring logic
- JULIANDAY() for date calculations
- Aggregate functions: SUM, COUNT, AVG, MAX, MIN
- GROUP BY, ORDER BY, WHERE filtering

## Author
Munna Naharki
github.com/munluns451
LinkedIn: linkedin.com/in/munna-naharki-6760883b9
