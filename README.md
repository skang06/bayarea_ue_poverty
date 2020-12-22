# Analysis of Unemployment, Poverty, and Life Expectancy in Bay Area, California with Vital Signs Data

## Background

An [editorial by the Baltimore Sun](https://www.baltimoresun.com/opinion/editorial/bs-ed-0207-baltimore-poverty-20190205-story.html) provided arguments for how a focus on poverty in Baltimore could solve a wide array of the issues in the city. The article mentions that people may turn to crimes like burglary at a higher rate if they have less economic security, and feel the need to engage in it for financial reasons. Moreover,  the article states that “people in low-income neighborhoods such as Upton Druid Heights consistently have more health problems … than people in wealthier areas such as Roland Park.” The fact that household income has consequences beyond what one may initially think, like health and crime rates, makes this a very important and interesting metric to delve into.

Additionally,[CBS Baltimore](https://baltimore.cbslocal.com/2017/07/06/life-expectancy-baltimore/) stated there are discrepancies in terms of life-expectancy in poorer areas of Baltimore. In fact, they had a life expectancy that was 20-years lower than that of richer areas. Lower life expectancy in poorer areas indicate that people are dying prematurely when these are preventable solutions, as those in richer areas are not dying so early. This problem is important as obviously we would like to create for a more equitable society, where people's livelihoods are not affected based on where they live- especially if there are ways to do so. 

In order to further corroborate the trends in different variables and the effectiveness of [Universal Basic Income (UBI)](https://www.investopedia.com/terms/b/basic-income.asp), which is when everyone receives a basic income from the government regularly, as a solution for Baltimore City's problem with poverty and inequitable life expectancy issue, we are looking into data from Bay Area, California. This is a wider data set from a big region of California, so the results can be applied to Baltimore City. 

## Business Question

___Would Universal Basic Income be an effective solution to reduce poverty, and thus increase life expectancy in poorer areas?___

## Open Data 

1.	__[Vital Signs Open Data](https://www.vitalsigns.mtc.ca.gov/)for Bay Area, California in 2012:__ 
- [Poverty data for cities](https://github.com/skang06/bayarea_ue_poverty_life_expectancy/blob/main/Bay_Area_Pov.csv):this dataset contains the original data source
- [Poverty Data for counties](https://github.com/skang06/bayarea_ue_poverty_life_expectancy/blob/main/poverty_county.csv):this dataset contains the original data source
- [Unemployment data for cities](https://github.com/skang06/bayarea_ue_poverty_life_expectancy/blob/main/Bay%20Area_UE.csv):this dataset contains the original data source
- [Life expectancy data for counties](https://github.com/skang06/bayarea_ue_poverty_life_expectancy/blob/main/County_LE.csvth):this dataset contains the original data source

## Python Notebook

Used Python and Google colaboratory to conduct analysis.
- __Bay Area Poverty, UE, Life Expectancy.ipynb:__ a Google Colaboratory notebook to aggregate data and make data visualizations [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1l_RpMEK-4JKqW8F8IoJrnVpjJeIaHDip?usp=sharing).

## Data Analysis

![alt text](https://github.com/skang06/bayarea_ue_poverty_life_expectancy/blob/main/Screen%20Shot%202020-12-06%20at%204.02.49%20PM.png)
As expected and demonstrated in the graph, those cities with lowest rates of poverty compared to others in the Bay Area, have higher unemployment rates in their particular city. Overall, unemployment rate and poverty have similar trends, meaning that they are either both higher are both lower comparably. However, the unemployment rate and the poverty rates do not demonstrate the strong direct relationship that was assumed. Interestingly enough, there are several cities where the poverty rate is higher than the unemployment rate. Nearly all the cities that have the highest rates of poverty in the Bay Area, based on the chart, have a lower unemployment rate than poverty rate in that city. 

This provides more evidence for the need for UBI. For most of the cities with the worst poverty, there is an unemployment rate that is not that high comparably. This could indicate that getting more disposable income is more of an effective solution to combating poverty than more jobs. 

![alt text](https://github.com/skang06/bayarea_ue_poverty_life_expectancy/blob/main/Screen%20Shot%202020-12-06%20at%204.02.58%20PM.png)

As shown in the combined line and bar graph there is a roughly inverse relationship between poverty rate and life expectancy. When poverty rate is lower, the life expectancy is higher. This helps to confirm the article that indicated the life expectancy is lower in places with more poverty. As this is a wider data set encompassing all counties in the Bay Area, we can assume we can apply to results to Baltimore City.
