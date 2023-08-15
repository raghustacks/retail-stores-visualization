# Retail-Stores-Visualisation-and-Analysis
## About Data
The dataset (Retail.xlsx) contains anonymised weekly sales data for 45 stores of a retail corporation that operates a chain of hypermarkets, discount stores and neighborhood stores. The data is available from the week of 11/11/2011 to the week of 26/10/2012. The stores offer five types of markdowns or discounts throughout the period of one-year. <br/>
There were four holiday weeks – 25/11/2011, 30/12/2011, 10/02/2012, 07/09/2012 in this one-year period. <br/>
There are three tabs in the Retail.xlsx excel file – Stores, Sales, and MarkDowns. Relevant information about the columns in these tabs is given below: <br/>
**Stores tab:** <br/>
- Store - the store number <br/>
- Type - the type of store (A - hypermarket, B – discount store, C – neighbourhood store) <br/>
- Size - the size of store (in square feet) <br/>

**Sales tab:** <br/> 
- Store - the store number <br/>
- Dept - the department number <br/>
- Date - the week (in dd-mm-yyyy format) <br/>
- Weekly_Sales - net weekly sales for the given department in the given store <br/>
- IsHoliday - whether the week is a holiday week or not <br/>

**MarkDowns tab:** <br/>
- Store - the store number <br/>
- Date - the week (in dd-mm-yyyy format) <br/>
- MarkDown1-5 - five different promotional markdown or discount types. Data in these five columns correspond to absolute markdown values. Markdown rates i.e., discount percentages are not given. Also, these markdown values are not available for all stores at all time. Any missing value is marked with a 0 <br/>
- IsHoliday - whether the week is a holiday week <br/>

## Visualisation using Tableau:
A Tableau dashboard is created that can help analyse the sales patterns across stores and their departments.<br/>
The dashboard consists of two controls that will work across entrie dashboard: <br/>
- A Month,Year filter
- A user control to select either one of the five markdowns or total markdown <br/>

***The dashboard consists of three visualisations-*** <br/>
- a dual-axis visualization showing sales & markdowns by week
  - sales during holiday weeks should be colored differently from sales during non-holiday weeks
- a dual-axis visualization showing sales & markdowns by store 
- a visualization showing top five departments by sales within each store

## Retail Stores Visualisation - Dashboard
A sample view of the Tableau dashboard for Retail Stores analysis

![Image of Retail store Visualisation-Dashboard](https://github.com/yogeshwaran-shanmuganathan/Retail-Store-Visualisation-and-Analysis/blob/master/Retail%20Stores%20Visualisation-Dashboard.png)

