# Business-Insights-360
## Problem Statement:
+ AtliQ Technologies is a company that sells hardware such as PCs, network and storage devices, and peripherals to various customers across the world.
+ Their customers are served through three different chanels: Retailer, Direct and Distributor. While they have grown substantially in recent years, the company has experienced significant losses in Latin America due to decisions based on limited surveys and intuition.
+ Additionally, AtliQ faces intense competition from Dell. Previously, AtliQ relied on large Excel files for data analysis.
To address these challenges and improve data transparency, the company has decided to hire a dedicated data analysis team.


## Task:
+ Create a dashboard tool for business review meetings and decision-making processes such as customer negotiations, marketing promotions, inventory management and finance budgeting.
+ Enable quick insights for the business across various customers to facilitate data-driven decision making.


## Project Implementation:
+ The project execution includes various steps:
+ - Connceting the MySQL database to power BI for importing the datset.
+ - Creating the required dimension table (dim_date) in Power Query using M language.
+ - Performing data transformation through Power Query.
+ - Data Modelling ( Creating relationship between different entities).
+ - Creating calculated columns and measures using more than 45 DAX formulas.
+ - Utilizing appropriate visuals as per the business requirement.
+ - Using field parameters and bookmarks to switch between two visuals.
+ - Creating dynamic titles based on applied filters.
+ - Creating tooltip to show sales trend analysis.
+ - Optimizing the report using DAX studio.
Utilizing Bookmarks to create  filter pane, which also shows the number of selected filters when you hover yur mouse over the button.
+ - Publishing the report to Power BI services.
+ - Setting up the personal gateway to enable automatic data refresh.


## Building the Dashboard:
+ - For Business Insights 360, I have created 5 multi-view dashboards, which serves the requirements of varoius stakeholders.

## Finance View:
 - The finance view indicates clear picture of organization's financial growth . The view includes KPIs such as Net Sales, Gross Margin %, and Net Profit%.
 - The Profit & Loss statement shows the progress of each metric, which allows users to filter by factors such as fiscal year, year-to-date, and year-to-go, etc.
 - The Area chart displays the comparision of selected measure in P&L statement with Benchmark numbers (LY or Target).

## Sales View:
 - The sales view access organization's growth at the customer level using Net Sales and Gross Margin metrics.
 - The scatter plot assist the stakeholders to identify customers that contribute significantly to organiztion's growth by displaying a comparison of Naet Sales and Gross Margin.
 - Donot chart displays the proportion of pre-invoice deductions, post-invoice deductions and Gross Margin.

## Marketing View:
  - The marketing view access organization's growth at the product level using Net Sales, Gross Margin and Net Profit metrics.
  - The scatter plot assist stakeholders in comparing Net sales with GM% or NP%.
  - The Donut chart displays the proportion of Gross Margi and Total COGS.

## Supply Chain View:
  - Supply chain view examines Net Error and Absolute Error by assesing key metrics based on actual sales quantity and forecasted sales quantit.
  - The column chart illustrates a comparision between the present forecast accuracy and that of previous year for each month, showing the Net Error.

## Excecutive View:
  - Customized for top level executives, showcasing top 5 customers & products by revenue contribution, along with the yearly trends in Revenue, GM%, NP% & Market Share%.
  - The Ribbon chart designed to analyze the market share% of top-tevel manufacturers for each fiscal year.
 -
