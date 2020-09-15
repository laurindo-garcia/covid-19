### Prototype Project
# Correlations between race, gender and poverty on Covid 19 morbidity and mortality in U.S. Counties

#### Objectives
1. Deepen understanding of the relationship between race/ethnicity, gender, poverty and severe health conditions and Covid 19 morbidity and mortality.
2. Apply skills recently acquired via Data Science skills towards advocacy that addresseses health disparities.

#### Method
This project was broken into 3 phases:

##### Phase 1: Exploration, Cleaning & Pre-Processing (<a href="https://github.com/laurindo-garcia/covid-19/blob/master/covid-19-race-gender-poverty-pre-processing.ipynb">See Phase 1 on Github</a>)
1. Source data on race/ethnicity, gender, poverty and severe health conditions and Covid 19 morbidity and mortality at the U.S county level
2. Clean and pre-process data according to unique identifiers

##### Phase 2: Statistical Analysis (<a href="https://github.com/laurindo-garcia/covid-19/blob/master/covid-19-race-gender-poverty-stats-EDA.ipynb">See Phase 2 on Github</a>)
1. Conduct exploratory data analysis
2. Test hypothesis that no relationship exists between features using statistical regression (Ordinary Least Squares).
3. Articulate conclusions and next steps for Statistical Analysis Phase.

##### Phase 3: Machine Learning (<a href="https://github.com/laurindo-garcia/covid-19/blob/master/covid-19-race-gender-poverty-machine-learning.ipynb">See Phase 3 on Github</a>)
1. Test hypothesis that features with highest importance are unable to predict Covid 19 morbidity and mortality using machine learning (Random Forest).
2. Visualise findings: a) Highly correlated features and possible Simpsons Paradox; b) outcomes of machine learning.
3. Articulate conclusions and next steps for Machine Learning Phase

##### Next Steps:
1. Implement improvements to fine tune each phase (notes contained in each section)
2. Continue testing model with fresh data, testing and algorithms
3. Seek out peer review and collaborations

#### Data Sources
1. Covid 19 Morbidity by U.S Count (USA Facts/U.S CDC, 2020): timeseries from 22/01/2020 to 31/07/2020: https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/
2. Covid 19 Mortality by U.S. County (USA Facts/U.S. CDC, 2020): timeseries from 22/01/2020 to 31/07/2020: https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/
3. Poverty Universe, All ages, by U.S County (SAIPE, U.S Census, 2019): https://www.census.gov/data/datasets/time-series/demo/saipe/model-tables.html
4. Annual County Resident Population Estimates by Age, Sex, Race, and Hispanic Origin (U.S Census, 2019): https://www.census.gov/data/tables/time-series/demo/popest/2010s-counties-detail.html
5. Severe COVID-19 Health Risk Index by U.S County (Policy Map/NY Times/2017 SMART-BRFSS, U.S CDC, 2017): https://www.policymap.com/download-covid19-data/

#### Acknowledgments
Thanks to:
1. My instructors Andrew Worsely, Lydia Peabody, the team at General Assembly and my peers in GA Data Science June-August 2020.
2. Julian Hatwell
