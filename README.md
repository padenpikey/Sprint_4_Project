# Sprint_4_Project
Version 1.2
by Paden Pikey

https://public.tableau.com/app/profile/paden.pikey/viz/Sprint4_Superstore_Project_Paden_Pikey/StrategicAdvertising?publish=yes

## Comments / Updates
Hi Dmitrii,
Thanks for reviewing my project and providing thoughtful feedback. I acted on most of your advice, whether optional or required.
For Part 1, I arranged the 'Stop Selling These Products' graph in descending order for profit, added profit loss formatting to bars themselves in '$', and filtered the graph to only show x<= -$1500 products since there was an infinite amount near $0. For 'Subcatecory Focus', I made the bar chart horizontal to better illulstrate profit v loss. 
For Part 2, I added color to the bar charts as suggested, changed the format to show units in '$' on the Y-axis and  the exact advertising cost in '$' placed above each bar (state), but also provided the cost per state below. 
For Part 3, I filtered to limit the amount of customers and products shown for returns and added color in the marks area.
Lastly, I created three dashboards as recommeneded, to illustrate relevant and easy to understand findings to stakeholders. Thanks for your help! I hope it meets the standard. 

## Part 1: Profits & Losses
  Subcategory + Region (worksheet)
When comparing the two dimensions above with the measure of profit, you can clearly see what subcategories generate profit or lose money by region.
  Segment + Category (worksheet)
When comparing the two dimensions above with the measure of profit, you can see broader categories broken down into customer segement. 
  Stop Selling These Products (worksheet)
Here is a barchart showing product IDs, that make less than $0 or profit and should be consindered to stop selling or to change the strategic approach.
  Subctegory Focus(worksheet)
This visulization depicts the three best performers and three worst performers via subcategories dimension in regard to profit.

## Part 2: Advertising 
  AVG Profit Per State (worksheet)
I needed to find the top three states with highest average profit. The chart shows the top profit earning states in descending order.
  Month and States to Advertise In (worksheet)
I created a calculated field allowing advertisement cost to be 20% of the profit for the top three highest earning states and the highest earning month of those states.The visuliation shows the three most profitable states in the best month of the year.
### Cost Per State
The company should be willing to spend $ _____ per ______ state in advertising in the month of October:
$1800.82 for Indiana 
$194.95 for Missouri
$171.58 for Minnesota

## Part 3: Returned Items
After left joing the returns table with the orders table and creating a calculated field where the null values are 0 and the 'Yes' values are 1, I could answer further questions.
  Products With High Return Rates (worksheet)
This visualization shows the most returned Product IDs in descending order.
  Customers With High Return Rates (worksheet)
This visualization shows the Customer IDs with the most returns in descending order. 
  Profit v. Return (worksheet)
This visualization shows the profit v. return of the subcategories dimensions, further suggesting what product types should or shouldn't continue being sold. 
