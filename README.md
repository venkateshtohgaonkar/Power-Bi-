**********Business Insights 360************

*******Project Overview******

**AtliQ Hardware**, a fast-growing manufacturer and distributor of computers and peripherals, is adopting Power BI for advanced data analytics. Previously, the company relied on Excel for analysis, but this approach lacked the depth needed for strategic decision-making, leading to inefficiencies and financial losses—especially in the Latin American market.

To overcome these challenges, AtliQ Hardware launched the Business Insights 360 project, leveraging 1.8 million transaction records from Excel, CSV, and MySQL to create a Power BI dashboard that provides:

***Finance Analytics***: Profit & Loss statement to track financial performance.

***Sales Insights***: Identify top/bottom customers and key sales metrics.

***Marketing Analysis***: Evaluate product performance to refine strategies.

***Supply Chain KPI***: Assess efficiency using forecast accuracy, net error, and other key metrics.

***Executive Dashboard***: A high-level summary for leadership decision-making.

***Product Performance***: Highlight top/bottom 5 products based on GM% growth YoY and post-discount trends.

This project enables data-driven decision-making and helps AtliQ Hardware stay competitive in the market.

Project Explanation
**Linkedin Post** : https://www.linkedin.com/feed/update/urn:li:activity:7307291130738446337/
**Company Summary**: AtliQ Hardware
AtliQ Hardware is a global company that manufactures and sells computer hardware and accessories like PCs, printers, USBs, and more. The company operates through three sales channels:

**Retailers** – Partners like Croma, Best Buy, Amazon, and Flipkart sell AtliQ products to consumers.
**Direct Sales** – AtliQ operates its own stores, including AtliQ E-store and AtliQ Exclusive.
**Distributors** – In some countries, government regulations require sales through distributors like Neptune.
Why Analytics?
**AtliQ Hardware recently faced unexpected losses in the U.S. market due to decisions based on surveys, intuition, and basic Excel analysis. Meanwhile, competitors use advanced analytics to drive their business decisions. To remain competitive, AtliQ is now building a dedicated analytics team to improve decision-making across key departments**:

**Finance – Track revenue, profits, and financial performance.**
**Sales – Identify top customers and sales trends.**
**Marketing – Measure product performance and optimize campaigns.**
**Supply Chain – Improve efficiency with key operational metrics.**
**Executive Insights – Provide leadership with data-driven decision-making tools.**
**Product – Analyze top and bottom-performing products to optimize growth and pricing strategies.**
With data analytics in Power BI, AtliQ Hardware aims to transform its business strategy and ensure long-term success.

Questions to Ask Before Building the Dashboard
1) What is the main goal of this Power BI dashboard?.
2) How will we measure the success of this project?
3) Do stakeholders want to see a preview before the final release?
4) What are the stakeholders’ expectations and concerns about this project?
5) Who will use this dashboard, and how will they use it?
6) What potential challenges might arise during development?
7) What data sources and resources are needed to build the dashboard?
8) Do stakeholders have any specific design or layout preferences?
9) What is the project deadline?
10) What do stakeholders expect to achieve by the end of this project?

    
After the project kickoff meeting, the data engineering team has provided the requested data. Let’s explore it.

Dataset Understanding:
Understanding the available data is crucial before starting the analysis. This dataset consists of dimension tables (static data like customer and product details) and fact tables (transactional data).

**Customer Data**
74 customers across 27 countries/markets.
209 stores operating on two platforms: a. Brick & Mortar: Physical stores (e.g., Croma, Best Buy), b. E-commerce: Online stores (e.g., Amazon, Flipkart)

**Market Data**
27 markets grouped into 7 sub-zones across 4 regions: a. APAC (Asia-Pacific) b. EU (Europe) c. NA (North America) b. LATAM (Latin America)

**Product Data**
3 divisions: a. Networking & Storage (N & S) b. Peripherals & Accessories (P & A) c. PCs (Notebooks & Desktops)
6 segments and 14 product categories (e.g., Internal HDD, Keyboards)

**Fact Tables (Transactional Data)**

**Fact Sales Monthly**: Sales quantities for each product.

**Fact Forecast Monthly**: Predicted customer demand to improve planning and reduce storage costs.
Additional Data Sources (Excel Files)

**Market Share**: Total sales data, including competitors (737 records)

**Operational Expense**: Advertising, promotions, and operational costs (113 records)

**NS GM Target**: Sales targets set by management for the current fiscal year (321 records)
