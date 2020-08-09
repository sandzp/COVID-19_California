# Tracking the Spread of COVID-19 in California

A graphical analysis/report of the spread of COVID-19 Through California

I utilized Geopandas to create choropleth maps to demonstrate the spread of COVID-19 through California from March - July 2020. 

The maps were created using 3 datasets (all included in repo):
1. COVID-19 cases by county (https://data.chhs.ca.gov/dataset/california-covid-19-hospital-data-and-case-statistics)
2. 2018 Census data (https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-total.html)
3. California Geographic boundaries (https://data.ca.gov/dataset/ca-geographic-boundaries)

Briefly, incidence, prevalence and mortality are common epidemiological indices: <br/>
**Incidence:** Number of new cases ÷ Population <br/> 
**Mortality:** Total number of deaths ÷ Population <br/>
**Prevalence:** Total number of cases ÷ Population <br/>

A Jupyter notebook containing the steps utilized to create the choropleths is included in the repo including explanations of the steps. All the maps were created individually and combined into a single figure to demonstrate the spread over time.  

I also included a labelling function that automatically labelled each county, if its incidence/mortality/prevalence rates were > mean statewide of the respective metric for that month. 

This work was part of a larger analysis into the health and socioeconoic effects of COVID-19 in California. 

