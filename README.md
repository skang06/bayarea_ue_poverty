# Analysis of Unemployment, Poverty, and Life Expectancy in Bay Area, California with Vital Signs Data

## Background

The metric of household income is an important contributor to many different aspects of life. An [editorial by the Baltimore Sun](https://www.baltimoresun.com/opinion/editorial/bs-ed-0207-baltimore-poverty-20190205-story.html) provided arguments for how a focus on poverty in Baltimore could solve a wide array of the issues in the city. The article mentions that multiple issues in the city can be correlated to poverty. For instance, people may turn to crimes like burglary at a higher rate if they have less economic security, and feel the need to engage in it for financial reasons. Moreover, The Baltimore City Health Department that poverty has been correlated with health issues as well. The article states that “people in low-income neighborhoods such as Upton Druid Heights consistently have more health problems … than people in wealthier areas such as Roland Park.” The fact that household income has consequences beyond what one may initially think, like health and crime rates, makes this a very important and interesting metric to delve into.

A look into Open Data from [Opportunity Atlas](https://www.opportunityatlas.org/) for household income will provide the means to explore how the financial trajectory of individuals in adulthood may be correlated with their parents' income and location at which they grew up.

## Business Question
___How ?___

## Open Data 
1.	__Opportunity Insights:__ this research group found the average household income from the 2014-2015 Census. A full data dictionary of column variables can be found [here.](https://github.com/skang06/baltimore-nassau-county/blob/master/glossary.txt)
- [Nassau County household income for those with parents' income in bottom 25th percentile](https://github.com/skang06/baltimore-nassau-county/blob/master/shown_tract_kfr_rP_gP_p25%20(11).csv):this dataset contains the original data source
- [Nassau County household income for those with parents' income in middle 50th percentile](https://github.com/skang06/baltimore-nassau-county/blob/master/shown_tract_kfr_rP_gP_p50%20(7).csv):this dataset contains the original data source


## Python Notebooks
Used Python and Google colaboratory to conduct analysis
- __Baltimore-Nassau-sunwookang.ipynb:__ a Google Colaboratory notebook to aggregate data and make data visualizations [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11teRC-rjrv8kMtpNIDOyBTZdIYh9PQTe#scrollTo=tbo5tE9SR066).

## Python Data Analysis

![alt text](https://github.com/skang06/baltimore-nassau-county/blob/master/Screen%20Shot%202020-11-22%20at%205.58.12%20PM.png)
![alt text](https://github.com/skang06/baltimore-nassau-county/blob/master/Screen%20Shot%202020-11-22%20at%205.58.31%20PM.png)
Python was used to measure how many people were below/above the poverty level for each income bracket. This produced almost identical results to the Excel data analysis, further supporting the conclusion that there were much more people above poverty in Baltimore across the income percentiles. Moreover, getting people in the 50th percentile made a big difference in lowering the amount below poverty in Baltimore. Additionally, Nassau had barely any below poverty. The slight error in getting some people below poverty in Nassau although the Excel data analysis did not, was that the in my Excel analysis, I realized had filtered out those with blank inputs for the different income percentiles because I had been able to see it clearly since I saw the data set all on one page. Howevver, using Python, I wasn't able to catch that.

![alt text](https://github.com/skang06/baltimore-nassau-county/blob/master/Screen%20Shot%202020-11-22%20at%205.59.15%20PM.png)
![alt text](https://github.com/skang06/baltimore-nassau-county/blob/master/Screen%20Shot%202020-11-22%20at%205.59.26%20PM.png)
Python was used to recreate the pivot charts that compared the different household incomes for those who came from differing household income backgrounds in the different neighborhoods of Baltimore. As demonstrated in the two graphs, they are both showing that there are pockets in both locations where household income is lower across all parent income distributions, as the Excel Data Analysis did. 

In conclusion, Python provided further support for my analysis as I receive the virtually the same mean, median, above/below poverty calculations and pivot charts. Therefore, I was able to able provide credibility to my original analysis. 

