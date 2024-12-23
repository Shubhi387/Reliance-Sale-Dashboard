# Reliance Sales Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/31b495b2-381f-44bf-bcce-246ce9371c4d/253353048d208b3a1cb6?experience=power-bi

## Problem Statement

This dashboard helps business to know insights of data. Businesses often struggle to derive actionable insights from complex and voluminous data, hindering their ability to make informed decisions. This Power BI report addresses these challenges by providing an interactive and comprehensive dashboard. It visualizes product brand performance, region-wise revenue distribution, and state-wise transaction data, enabling users to identify key contributors and trends. Additionally, the report includes month-over-month comparisons of revenue and profit, offering insights into growth areas and potential setbacks. By consolidating these metrics into a single, user-friendly interface, the report empowers decision-makers to monitor performance effectively and drive strategic business outcomes.


### Steps followed 

- Step 1  Load Data:

    Imported the dataset (CSV file) into Power BI Desktop.
    Data Cleaning and Transformation:

- Step 2 Opened the Power Query Editor to perform Extract,      Transform, and Load (ETL) operations:
    Cleaned the data by handling null values and duplicates.
    Verified and corrected data types for each column.
    Added calculated columns as required for the analysis.
- Step 3 Data Modeling:

    Loaded the cleaned data into Power BI and used the Model View to establish relationships between tables in the schema.
- Step 4 Creating Measures:

    Defined essential measures using DAX, including:
    Profit, Revenue, Transactions
    Year-to-Date (YTD) Revenue and Profit
    Previous Month metrics for Revenue, Profit, Transactions, and  Returns.
    Utilized DAX functions such as SUM, COUNTA, DISTINCT, DATESYTD, and PREVIOUSMONTH to calculate these values.
- Step 5 Building the Report:

    Added key metrics like Product Brand, Transactions, Quantity, Revenue, and Profit to visualizations.
    Used formatting options to rename and organize columns and measures for better clarity.
- Step 6 Data Visualization:

    Created interactive visualizations, including:
    Maps and Treemaps to visualize geographical and hierarchical data.
    KPI Cards for quick insights into key metrics.
    Customized charts and added labels using the formatting tools to improve readability.
- Step 7 Publishing:

    Published the finalized report to Power BI Service, making it accessible for stakeholders.

  (a) Revenue vs previous month

  (b) Profit vs previous month
  
  (c) Returns vs previous month 
  
  (d) Product Brand wise data
  
  (e) Region wise revenue
  
  (f) State wise Transactions
