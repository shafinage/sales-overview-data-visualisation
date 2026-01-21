# Retail Business Performance & Product Insights (Tableau)

## Project Overview
A retail company needs to analyze its transactional sales data and deliver insights to support strategic decision-making by the CEO and CMO.
The business has been performing well and is planning for future expansion. Leadership wants to understand:
- What drives revenue
- Which markets and products perform best
- How customer purchasing behavior affects growth
- Where expansion opportunities exist beyond the UK

### Dataset Description and Cleaning
The dataset contains transactional data from an online retail store, including:
- Country
- Invoice Date
- Invoice Number
- Customer ID
- Stock Code
- Quantity
- Unit Price
- Revenue was calculated as: Quantity*Unit Price

Before analysis, data quality checks were applied to ensure reliable insights:
- Transactions with Quantity < 1 were excluded (returns / errors)
- Transactions with Unit Price ≤ 0 were excluded (input errors)
This ensured the analysis reflects actual sales performance only.

## Questions Addressed
CEO-Focused Questions (Executive & Expansion View)
- Which countries generate the highest and lowest revenue?
- How does revenue trend monthly, and are there seasonal patterns?
- Which countries contribute to 80% of total revenue?
- Where is product demand strongest outside the UK?
- How does performance differ across key markets over time?

CMO-Focused Questions (Marketing & Customer View)
- Who are the top customers by revenue, and how concentrated is revenue?
- How frequently do customers purchase?
- Which products lead by revenue vs quantity?
- Which products sell high volumes but generate low revenue, and vice versa?
- Which products underperform and may require review?

Because the main business is located in the UK, the analysis is filtered by country selection (with and without the UK).

### [Dashboard 1 - Business & Market Overview](https://public.tableau.com/views/MarketandProductRevenue/SalesRevenueOverview?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- Total revenue
- Revenue trend
- Top & bottom countries by revenue
- Revenue density map
- Cumulative revenue (Pareto / concentration analysis)
- Monthly trends of revenue, quantity, and orders for top 3 countries

### [Dashboard 2 - Product & Pricing Insight](https://public.tableau.com/views/ProductandPricingInsight/Products?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- Top 10 products by revenue or quantity (parameter-driven)
- Bottom 5 products by revenue
- Customer purchase frequency distribution
- Unit price bands vs revenue and quantity contribution

### Key Insights
- Revenue is mostly concetrated in the European countries, with Australia showing strong demand, giving potential expansion
- Products of lower price ranges are more in demand and contributing to higher sales
