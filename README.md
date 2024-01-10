## Project's Title
**A sustainable learning approach Predict Scope 3 Carbon Emissions**

## Project Description
Scope 3 emissions have a significant impact on climate change due to their indirect nature and broad reach across the value chain. For most organizations, a substantial portion of their carbon emissions are attributed to activities within their supply chain and the post-sale phases, including product processing, usages, and end-oflife treatment, collectively referred to as scope 3 emissions. However, measuring
scope 3 emissions is challenging many companies because of its inherent difficulty
in calculation, the lack of consistent data, and the limited control over supplier’s
decision and customer’s behaviors. In this paper, we expand the idea of
implementing machine learning approach to estimate scope 3 emissions by
reporting another well-performing machine learning algorithm, which is Extra
Trees regressor. The model uses broadly available data including mandatory scope
1 and scope 2, financial statement data, and industry classification as input features
for predicting the scope 3 emissions target. In addition, we measure the
computational cost of running models in terms of execution times, power
consumption, and equivalent carbon emissions generated. The selected model is the
one balancing the trade-off between predictive accuracy and energy efficiency. We
also describe the trend of scope 3 emissions generation during the pandemic covid-
19 to examine the influence of globally unexpected events on the volume of scope
3 emissions produced. Finally, we predict scope 3 emissions across categories and
sectors to evaluate the model performance by examining different prediction
metrics and energy consumption coefficients

## Data
| Data categories |	Sources |	Description |
| --- | --- | --- |
| Target | Bloomberg, Refinitiv Eikon |	Scope 3_total, 16 scope 3 categories |
| Country information |	International Monetary Fund |	Country, GDP, Population, Carbon tax, Carbon Intensity |
| Financial data |	Bloomberg, Refinitiv Eikon | Total Assets, Capital Expenditures, Operating Expenses, SGA expense, Cost of Goods & Industrials Sold, Inventories, Revenue, Property Plant & Equipment Net, Inventories, Revenue, Asset Turnover, Inventory Turnover, Number of employees |                  
| Industry classification |	Refinitiv Eikon |	The Refinitiv Business Classifications (TRBC) is the global, comprehensive, industry classification system owned and operated by Refinitiv. It divided companies into 13 economic sectors: Energy, Basic Materials, Industrials, Consumer Cyclicals, Consumer Non-Cyclicals, Financials, Healthcare, Technology, Utilities, Real Estate, Associations & Organizations, Government Activity, Academic & Educational Services. |
| ESG metrics	| Bloomberg, Refinitiv Eikon	| CRS/Sustainability committee, ESG Disclosure score, ESG News Sentiment ES Positive, Emission scope 1, Emission scope 2 |


