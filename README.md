# Sales-Insights
Interactive dashboard using SQL and Power BI

Case - This was about a company which was facing issue to gather accurate business data from periodic sales all over their market regions in india where they were represented by their agents
Company: A Computer Hardware company with representatives across various market regions in India.

Challenge: The company lacked a centralized platform for stakeholders to access and analyze business data. This made it difficult to gain insights into regional performance and identify trends.

Solution: Develop an interactive dashboard using SQL and PowerBI which can provide detailed data for sale and business insights.

Step-by-Step Approach -

Data Gathering and Analysis:
-> Identify relevant data sources : This was provided in csv file format by the company from their database which was updated from all points of sale.
-> Created SQL queries to extract and transform the data for PowerBI. This involved filtering, aggregating, and joining tables based on requirements.
-> Data was analyzed to understand key performance indicators (KPIs) for each region (e.g., sales by region, revenue by market, product popularity etc).

PowerBI Desktop Development:
-> PowerBI Desktop was connected to the SQL database and query was imported in power query editor.
-> Data model was built by establishing relationships between tables based on common fields (star schema).
-> Created calculated columns and measures in DAX language for complex calculations not available in SQL (e.g., year-over-year growth, market share).

Dashboard Design:
-> Utilized various PowerBI visuals like bar charts, line graphs, maps, and pie charts to present KPIs effectively.
-> Implemented slicers, filters, and drill-down capabilities to allow users to explore data by region, product category, time period, etc.

Deployment and Sharing:(Required to performed from company,s end)
-> Publish the PowerBI report to the PowerBI service (online platform) for wider accessibility.
-> Control user access and sharing permissions based on roles within the company.
-> Train regional representatives on how to use the dashboard to gain insights and make data-driven decisions.


Conclusion - 

The interactive dashboard provides regional representatives with real-time access to business data and insights. This allows them to:
-> Monitor regional performance against set targets.
-> Identify trends and opportunities in their respective markets.
-> Compare regional performance with other regions or national averages.
-> Make informed decisions about sales strategies, resource allocation, and marketing campaigns.
