# coffee_sales_excel
Coffee sales analysis of two years of data for a small company. 

Excel || Caffeine Sales Analysis
Caffeine…the fuel intake everyone consumes; from stay-at-home moms to Fortune 500 executives. Today, I take on the role of data analyst for a small caffeine distributor in the United States. The year is 2012 and I’ve been given a dataset of sales numbers from 2010 and 2011, tasked with identifying key metrics and gaining insights the company can act on, and present my findings in the most relatable means for my stakeholders. And what better way to do that than a beautifully crafted dashboard?
Tools of Choice:
Excel – Pivot Tables, Pivot Charts, Filters, Slicers, and Map Charts

Key Insights:
- Total sales consistently decline in the last quarter of each year, but overall numbers are trending up.
- California proves to be the highest in sales and profit but surprisingly comes from mostly small market areas.
- The leader in the clubhouse among all major markets goes to the central United States, primarily Illinois.
- There are products costing the company money with little to no return value. However, these losses are easily identifiable in their corresponding markets.
- 45% (70 specific locations) of all geographical sales are underperforming.

Analysis:
Where to start? 
Well, with a first look at the data, which is happily free of typos, format issues, and null values, I find twenty fields of helpful metrics. There are four location-based columns signifying area codes, state, market location, and market size. The bulk of the data highlights numbers ranging from profit, marketing expenses, budgeted projections, category identifiers, cost of goods (COGS), total sales, and more. The last four columns are comprised of the date the product sold, the product type, the product name, and the type (regular or decaf).
The more granular non-numeric details I’m interested in diving into in hopes of gaining some perspectives are:
- 13 products (Caffe Latte, Columbian, Decaf Espresso, Green Tea, etc.)
- 20 US states
- 4 markets (Central, East, South, and West)
- 2 market sizes (Small and Major)
  
With a brief overview of the data contents and KPIs I intend to explore, it’s time to see what the numbers are trying to show me.
After turning the worksheet into a table, I created 4 separate Pivot Tables to highlight key aspects of caffeine sales. The first I use to look at the trend of total sales throughout the two-year history.
I’ve segmented the order dates by year and quarter and then pulled in two instances of the sum of total sales. The first instance shows me the sales in dollar value, while the second instance converts that number into the percent of total sales over the entire timeframe.
The company is relatively small and all sales cap off just below $820,000. But the future looks bright with noticeable growth within one year.
 

Knowing my employers would appreciate a visual aid, I created a Pivot Chart using the time series and sales in dollars to emphasize the growing trend in production. After some quick formatting and preemptive thoughts on a final dashboard, I’ve set the foundation for the rest of the analysis.
 

Moving on to the second Pivot Table, I create another useful overview of the data by replacing the time series with the list of products. Instead of sales, I opt to show the stakeholders the sum of profit from each grouping and its total expenses. It’s clear from the result that this deserves further analysis as there are wide variations in the outcome.
  

For instance, applying an additional filter to the Pivot Table shows me that market size plays a significant role in some of the losses the company is taking.
But before I dive deeper, I need to finish the foundational work. I created another Pivot Chart, utilizing a combo column chart for the profit and an area chart for the expenses. After some formatting tweaks to mimic the first chart, I’m ready to press on.
 
Pivot Table number three I’ll dedicate to the granular location data. Like the first Pivot Table, I’ll pull in the sum of the total sales, but instead of showing the purchase date, I’ll show the state. Now the stakeholders will have a better understanding of where their wins and losses are coming from.
 
I then went a little deeper and pulled in the various area codes for each state to view the partitions of the total sales. The results were interesting. I filtered on the area codes for each state that had a less than 25% share of their state sales. The lowermost 30% in sales of those filtered, equate to 51% of the bottom fourth performing areas. Meaning there are 70 area codes or 45% of all areas that deserve further investigation to determine their profitability and any future actions to benefit the company.
Furthermore, select products offer no value when sold in designated locations. Caffe Mocha’s, an Espresso product type, for instance, has a negative profit margin when sold in the New York area.
 
Because this is location data, I can visualize this with a Map chart. Unfortunately, Map charts aren’t an available option within Pivot Charts in Excel. So, I make the data static by copying and pasting the state and sum of sales values beside the Pivot Table and now I can generate a map of the US, highlighting the areas of interest.
 

For my last Pivot Table, I’ll use the various markets and list their total sum of margin, which is the sales less the cost of goods sold (COGS).
 
Using a simple bar chart and matching the existing formatting, I have the final chart for my presentation of data.
 

With all that complete, I open a new worksheet, insert some objects and formatting, and then copy my existing charts into the new dashboard. After applying a timeline and some slicers, the data is ready to be presented for consideration.

 


Recap and Suggestions:
-  With 45% of all locations accounting for subpar sales performance, evaluation for further marketing efforts or a decrease in production is needed.
- Significant losses of product sales have been identified by market size and market location. It is recommended that these products no longer be offered in these instances.
- Sales numbers in Q4 have consistently declined following historically beneficial quarters. More data is required to determine causality and potential correction. Perhaps a marketing adjustment or cutback in expenses for this time period.
