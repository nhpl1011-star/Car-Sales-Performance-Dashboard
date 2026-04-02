# Car-Sales-Performance-Dashboard

## **1. Short Description / Purpose**
The Car Sales Performance Dashboard is a dynamic and data-driven Power BI report designed to track and analyze automotive sales performance across various dealer regions. The dashboard focuses on highlighting key metrics such as YTD/MTD sales, Year-over-Year (YoY) growth, and customer preferences regarding body styles and colors. This tool is intended for sales managers, dealership owners, and business analysts who seek to identify high-performing trends and optimize inventory strategies based on real-time data insights.
## **2. Tech Stack**
The dashboard was built using the following tools and technologies:

Power BI Desktop – Main data visualization platform used for report creation and interactive dashboard design.

Power Query – Data transformation and cleaning layer (ETL) used to reshape and prepare automotive sales data.

DAX (Data Analysis Expressions) – Used to create complex calculated measures such as YTD/MTD Sales, YoY Growth, and Dynamic High-Point Markers.

Data Modeling – Established a robust Star Schema (Relationships between Sales, Calendar, and Car Detail tables) to enable seamless cross-filtering and accurate time intelligence.
## **3. Features / Highlights**
### Business Problem
*In the highly competitive automotive industry, sales managers and stakeholders often struggle to track real-time performance across multiple regions. Raw transactional data makes it difficult to answer critical questions quickly:

Which car models are driving the most revenue this year?

How does our current monthly performance compare to the same period last year?

Are there specific regions or car colors that are underperforming?

What is the weekly sales momentum, and are we hitting our targets?

### Goal of the Dashboard
To deliver an interactive, data-driven visual tool that:

Monitors Core KPIs: Tracks YTD/MTD Sales, Average Price, and YoY Growth at a glance.

Analyzes Market Trends: Identifies customer preferences in car body styles and colors.

Optimizes Inventory: Helps dealerships align their stock with regional demand and top-selling models.

Enhances Decision-Making: Provides a "drill-down" capability from high-level executive summaries to individual transaction details.

### Walkthrough of Key Visuals
Executive KPI Cards (Top): Displays critical metrics like YTD Total Sales, YTD Cars Sold, and YoY Growth % to give an immediate health check of the business.

Sales Weekly Trend (Line Chart): A dynamic timeline that tracks sales fluctuations, featuring a High-Point Marker to celebrate and analyze record-breaking weeks.

Regional Distribution (Map Chart): An interactive map that visualizes sales volume by dealer region, making it easy to spot geographic "hot zones."

Sales by Body Style & Color (Pie/Donut Charts): Breaks down revenue by car aesthetics, revealing whether SUVs, Sedans, or specific colors like Black/White are dominating the market.

Company-Wise Sales Grid: A tabular view with Sparklines or Data Bars to compare the performance of different car brands side-by-side.

Details Transaction Grid: A comprehensive table at the bottom for granular auditing, showing every sale’s model, date, price, and dealer info.

### Business Impact & Insights
Inventory Optimization: Dealerships can reduce "dead stock" by ordering car styles and colors that the dashboard identifies as high-demand.

Sales Strategy: Regional managers can reallocate marketing budgets to underperforming areas identified on the map.

Growth Tracking: The YoY analysis provides a clear benchmark, helping the company stay on track for annual targets.

Operational Efficiency: Reduces the time spent on manual reporting by providing an automated, "single source of truth" for all sales data.
