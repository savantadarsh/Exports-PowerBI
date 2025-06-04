# Infinity Exports Performance Summary 2024 - An Exploratory Guide

![OverView](assets/Overview.png)

## **1. Introduction**
This Power BI dashboard provides a comprehensive analysis of Infinity Exports' financial performance in 2024. Interactive visuals allow stakeholders to explore revenue trends, customer performance, product strengths, delivery strategies, and business categories. It offers a strategic overview of sales activity and profitability for informed decision-making.

**Why This Dashboard is Useful**
- **Revenue and Profit Tracking**: Instant visibility into key metrics such as total revenue (£1.04B), total units sold (62.23M), and average profit margin (44.92%).
- **Trend Analysis**: Weekly sales line chart shows fluctuations in both revenue and quantity sold over time, including demand spikes and downturns.
- **Product Performance**: Revenue by Product Category highlights top-earning product types and pricing distribution.
- **Customer Insights**: A breakdown of revenue by Customer Name helps identify major contributors and strategic accounts.
- **Business Category Breakdown**: Segmentation into Retail, Bulk, and Others reveals revenue share and profitability by sales model.
- **Delivery Mode Impact**: Delivery Mode chart (Air, Land, Sea) shows revenue distribution across logistics strategies.

**How to Use This Dashboard for Decision-Making**

1. Use the **Country Filter** to evaluate market performance across geographies.

   ![OverView](assets/Country.gif)

2. Use the **Month Filter** to track monthly revenue and profit trends and identify seasonal patterns.

   ![OverView](assets/Month.gif)

4. Explore **Product Category** filters to analyse demand and pricing trends.
   
5. Leverage **Customer View** to assess top-performing clients for retention and upsell strategies.
6. Analyse the **Weekly Sales Chart** for planning inventory and campaign timing.
7. Review **Delivery Mode Distribution** to support logistics cost control and sustainability.
8. Use **Business Category Segmentation** to tailor pricing and volume strategies.
9. Hover over charts to get additional information from tooltips. 

## **2. Dataset and Key Measures Used**
The dashboard integrates transactional, customer, and logistics data to track performance and drive insights.

**Datasets Used**
- **Transactions**: Contains sales data, revenue, profit, and transaction details
- **Products**: Includes product pricing, costs, and categories
- **Customers**: Segments customers by name and business type (Retail, Bulk, Others)
- **Logistics**: Tracks shipment methods (Air, Land, Sea)

**Key Measures Used in Power BI**
- **Percenatage(%) of Total Revenue**: Determines each country’s share of total global revenue
- **Quantity Percentage(%) of Product Category**: Calculates what portion of total units sold is attributed to each product category
- **Revenue Percentage(%) of Product Category**: Measures each product category's contribution to total revenue
- **Profit Percentage(%)**: Calculates net profit as a percentage of revenue
-  **Product Profit**: Determines the per-unit profit for each transaction
- **Total Profit**: Aggregates total profit across all products and transactions
- **Total Revenue**: Calculates the gross revenue from all product sales
- **Week Number**: Extracts the week number from each transaction date for time-series analysis

## **3. Key Insights and Business Implications**
This dashboard provides interactive and data-driven insights into Universal Export’s financial performance. By utilizing filters and dynamic visualizations, it allows stakeholders to explore revenue trends, track product performance, compare sales across regions, and evaluate the impact of logistics decisions.

The key insights below highlight how users can extract business intelligence from the dashboard and how these findings can drive strategic decisions.

### **A. Sales & Profit Trends Across 2024**

**Findings**:
- **Total Revenue**: £1.04B
- **Total Units Sold**: 62.23M
- **Profit Margin**: 44.92%
- Highest weekly revenue reached ~£22M; sharp dip to £3M and £0.16M toward year-end.

**Business Implications**:
- The year-end drop requires investigation — potentially a data lag, shipping constraints, or seasonal slowdown
- Strong mid-year performance indicates ideal periods for campaigns and stocking

**How the Dashboard Helps**:
- The **Month Filter** allows users to analyse revenue and profit month by month, helping identify key seasonal patterns.
- The **Revenue by Week Chart** provides a detailed breakdown of fluctuations, allowing users to compare performance on a granular level.
- Users can combine filters (e.g., selecting a month + country) to explore regional differences in sales trends.

ToolTip
**Country-wise % Revenue Contribution**
💰 **Revenue Concentration Analysis**: Helps identify over-reliance on specific countries, allowing diversification strategies to reduce financial risk and improve revenue stability.

📈 **Market Investment Prioritisation**: Guides decisions on where to allocate marketing or expansion budgets to maximise returns from high-performing or high-potential regions.
UK Revenue Share: 23.92% of total revenue in 2024
➤ With total revenue at £1,040M, the UK contributes approximately £248.8M in revenue.

Implication for Investment: Being the top market, the UK justifies further resource investment (e.g., campaigns or infrastructure) to reinforce and grow revenue.

![OverView](assets/perc_revenue.gif)


### **B. Product Performance: Strengths and Weaknesses**

**Findings**:
- Top categories by revenue: Jacket (£225.4M), Cardigan (£155.2M), Hoodie (£143.3M)
- Lower performers: Sweatshirt (£52.2M) and T-Shirt (£48.1M)
- Price points vary from £6 to £40 per unit

**Business Implications**:
- Strong jacket sales suggest a focus on premium outerwear; consider regional expansions or bundled winter collections.
- Underperformers may benefit from repositioning, design refresh, or targeted discounts.

**How the Dashboard Helps**:
- The **Revenue by Product Category Chart** clearly distinguishes top-performing and underperforming products.
- By using the **Country Filter**, users can analyse how different product categories perform across regions.
- Combining **Month + Product Category** filters helps assess seasonality in product sales.

ToolTip
**Product-Level Financial Summary**
📊 **Profitability Assessment**: By showing product-wise profit and cost, it helps finance teams evaluate which products are most financially viable or eroding margins.

⚖️ **Pricing and Cost Optimization**: Enables informed decisions around pricing strategy or cost control initiatives to improve profit margins per product.
Product Profit in May (UK): £63.70M

Product Cost in May (UK): £79.62M

Profit Margin: 44.44%
➤ These numbers suggest that despite high operational costs, pricing is optimised for healthy margins — ideal for further margin scalability through volume.

![OverView](assets/fin_num.gif)

Product Revenue vs Quantity Table
💡 Margin vs Volume Trade-Off: Shows whether high-volume products are generating enough revenue to justify their scale, enabling correction of financially inefficient product lines.

📦 Revenue Contribution Clarity: This section highlights which products are driving disproportionate revenue, supporting the reallocation of resources to high-yield items.
Top Contributing Products (UK – May):

Jacket: 9.45% quantity, 22.51% revenue

Cardigan: 7.78% quantity, 13.90% revenue

Polo Shirt: 7.50% quantity, 9.83% revenue

Insight: High-revenue-to-quantity ratios for Jackets and Cardigans suggest premium positioning with strong financial return per unit sold.

![OverView](assets/detail_prdts.gif)

### **C. Regional Performance and Major Clients**

**Findings**:
- Leading countries: UK (23.9%), Spain (9.4%), France (6.2%)
- Top clients: Panowikk (£26.9M), TOL Uniform, General Clothing
- Over 25 clients contribute between £24M–£27M each

**Business Implications**:
- Market concentration in the UK indicates a need to diversify regionally for risk balance.
- Client contributions are relatively flat at the top — a strong mid-tier client base should be cultivated further.

**How the Dashboard Helps**:
- The **Revenue by Customer Chart** helps identify high-value clients.
- The **Country Filter** allows users to compare revenue distribution by region.
- The combination of **Month + Country** filters provides insights into seasonal variations in regional sales.

Salesperson Profile
🎯 Attribution of Sales Revenue: Helps attribute revenue outcomes to specific individuals or teams, which supports performance-based incentives and territory ROI analysis.

🧭 Territory Profitability Mapping: Enables finance and sales leaders to track which territories or reps contribute most to financial goals, guiding hiring or training investments.

Salesperson Country: South Africa

Gender/Nationality: Female, South African

Implication:
➤ Revenue from the UK in May is indirectly driven by international sales agents, supporting remote sales efficiency.
➤ Performance attribution to this rep can aid in refining commission/incentive models and improving resource planning for the UK territory.

![OverView](assets/salesperson.gif)


### **D. Sales Channel & Logistics Impact**

**Findings**:
- Revenue by business category: Bulk (41.6%), Others (36.5%), Retail (21.9%).
- Delivery Mode split: Air, Land, Sea (35%), Land (30%), Air (25%), Sea (10%).

**Business Implications**:
- Heavy reliance on bulk buyers opens an opportunity for customised pricing and loyalty incentives.
- High usage of air freight (25%) impacts margins; shifting more volume to sea could improve cost efficiency.

**How the Dashboard Helps**:
- The business category pie chart clarifies where profit optimisation strategies should focus.
- Delivery Mode visual guides shipping and sustainability decisions.

ToolTip
Revenue by Delivery Mode
🚚 Cost-Efficiency Insights: Allows evaluation of how logistics methods align with revenue, identifying opportunities to shift toward more cost-effective delivery modes.

🌍 Sustainability-Linked Profitability: Supports financial modeling of eco-friendly logistics shifts, ensuring cost savings do not compromise high-value delivery routes.
Air, Land, Sea (mixed): 35%

Air only: 30%

Land: 25%

Sea: 10%

Insight:
➤ 65% of revenue flows through air (alone or mixed), indicating high delivery costs tied to speed.
➤ Financial opportunity lies in gradually shifting 10–15% to land/sea to optimize cost without compromising service.

![OverView](assets/Delivery.gif)

### **E. Sustainability Initiative: Delivery Mode Strategy**

**Findings**:
- ~25% of revenue tied to air shipments; most expensive and highest carbon impact
- Combined air/land/sea mode is the largest contributor (35%)

**Business Implications**:
- Reducing air dependency can lower costs and support green initiatives
- Must be balanced with delivery timelines and customer expectations

**How the Dashboard Helps**:
- The Delivery Mode chart enables simulation of the potential impact of shifting the logistics strategy
- Combined with Country/Product filters, users can identify which markets rely heavily on fast delivery

## **4. Final Business Recommendations**

1. **Focus on Premium Products**: Expand high-performing categories like Jackets and Hoodies.
2. **Reduce Logistics Costs**: Gradually shift air shipment volumes to sea, where feasible
3. **Diversify Regional Exposure**: Target emerging markets to reduce UK dependency
4. **Strengthen Mid-Tier Clients**: Offer loyalty incentives to grow £24M–£25M tier accounts
5. **Phase Out Underperformers**: Reassess Sweatshirt and T-shirt strategies

## **5. Next Steps**
- **Predictive Sales Forecasting**: Use Power BI trendline data to estimate 2025 monthly volumes.
- **Customer Segmentation Deep-Dive**: Use filters to cluster by revenue, retention, and geography
- **Operational Refinement**: Evaluate warehouse/delivery schedules based on weekly demand swings

## **6. Conclusion**
This Power BI dashboard provides critical insight into Infinity Exports’ performance in 2024. It empowers leaders to make data-backed decisions across product strategy, logistics, and customer engagement. With clear visibility into revenue trends and operational levers, the organisation is well-positioned to refine execution and accelerate export growth into 2025.




[here](assets/Output/1b.pdf).





















