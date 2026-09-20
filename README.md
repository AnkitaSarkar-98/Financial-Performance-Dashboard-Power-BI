# Financial-Performance-Dashboard-Power-BI


Overview
This project is a Financial Performance Dashboard created using Microsoft Power BI. The purpose of the dashboard is to provide a clear and interactive view of a company's financial performance.
The dashboard helps users analyze:
- Revenue and Revenue Budget
- Gross Profit and Gross Margin %
- EBITDA and EBITDA %
- Budget Variance and Budget Variance %
- Cash Inflows, Cash Outflows and Net Cash
- Product vs Service Performance
- Receivables Aging
- Monthly and yearly financial trends
Interactive filters are provided for Period, Region, and Product Category, allowing users to explore the data from different perspectives.

Tools & Technologies

Power BI
Used to build the interactive dashboard, data model, KPIs, charts, filters, and financial visualizations.
Power Query
Used for:
- Data cleaning and transformation
- Correcting data types
- Creating and formatting date fields
- Creating the DimMonth table
- Removing unnecessary data
- Preparing the dataset for analysis

DAX

Used to create calculated measures and financial KPIs.

 Method
 
The project followed a structured data-analysis process:
1. Data Preparation
The raw financial dataset was imported into Power BI and cleaned using Power Query.
2. Data Modeling
A simple dimensional model was created with:
- FactFinancial
- DimMonth
- DimRegion
- DimProduct
Relationships were created between the fact table and dimension tables to support filtering and analysis.
3. DAX Measures
DAX measures were created for revenue, budget, profitability, cash flow, and variance calculations.
4. Dashboard Development
Different visuals were created to communicate the financial results clearly.
5. Interactive Analysis
Slicers and filters were added for:
- Period
- Region
- Product Category
This allows users to dynamically explore the dashboard.
   Dashboard Visuals
The dashboard contains:
- Revenue KPI
- Gross Margin % KPI
- EBITDA % KPI
- Net Cash KPI
- Revenue – Actual vs Budget
- Revenue & Gross Profit Trend
- Budget Variance % Trend
- Product / Service Performance
- Receivables Aging Distribution
- Cash Flow Waterfall

   Key Insights
  
The dashboard provides a quick understanding of the company's financial position.
Some of the main observations include:
- Revenue is approximately $23.6M in the overall dashboard view.
- Gross Margin is approximately 45.5%.
- EBITDA Margin is approximately 24.8%.
- Net Cash is approximately $688K.
- Product revenue is higher than Service revenue in the displayed overall view.
- Actual revenue is below budget in many of the displayed months.
- Budget Variance % is therefore negative across many periods.
- The Cash Flow Waterfall shows the relationship between cash inflows, cash outflows, and net cash.
- Receivables are analyzed using aging buckets such as 0–30 Days and 31–60 Days.

 Conclusion
 
This project demonstrates how Power BI, Power Query, and DAX can be combined to transform raw financial data into an interactive business intelligence dashboard.
The dashboard makes it easier to monitor financial KPIs, compare actual performance with budget, analyze profitability, understand cash flow, and explore product, service, and receivables performance.
It also demonstrates the importance of data cleaning, data modeling, DAX calculations, and effective visualization when building a financial reporting solution.

Thank you for taking the time to check out this project! Your interest, feedback, and contributions mean a lot.
If you have any suggestions or improvements, feel free to share them.
Don't forget to ⭐ star this repository if you found it helpful — it really helps others discover the project too.
Happy coding
