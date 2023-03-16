# COVID-19-Dashboard
This is a dashboard I made in Google Sheets using a fictitious COVID-19 dataset from Kaggle. 
The dataset came with a total of 8 columns
1. Serial Number	
2. Country	
3. Total Cases	
4. Total Deaths	
5. Total Recovered	
6. Active Cases	
7. Total Test	
8. Population

I created the following calculated fields to perform my analysis and draw insights from the data
1. Rate of infection
2. Death rate
3. Recovery rate
4. Rate of positive tests


In this dashboard, I analyzed visualized 5 key metrics from the dataset that I believed would provide the most insights to the effects of the disease. The metrics are based on the top 5 countries with the;
- Highest Infection Rates
- Highest Death Rates
- Highest Recovery Rates
- Highest Number of Active Cases
- Highest Rates of Positive Cases

![](https://github.com/imanjokko/COVID-19-Dashboard/blob/main/Dashboard.jpg)

## Audience
- Epidemiologists
- Public Health professionals
- Other Medical professionals
- Anyone seeking to understand the effects of COVID-19

## Charts
1. **Highest Infection Rates-** this is the number of individuals who got infected for every 100 people in the population. This was calculated using the following formula: **(Total cases / Population) * 100**
2. **Highest Death Rates-** this is the number of patients who died out of every 100 confirmed cases of COVID-19. This was calculated using the following formuala: **(Total deaths / Total cases) * 100**
3. **Highest Recovery Rates-** this is the number of cases where patients recovered out of every 100 confirmed cases of COVID-19. The was calculated using the following formula: **(Total recovered / Total cases) * 100**
4. **Highest Number of Active Cases-** this is the number of on-going cases, as at the time of data gathering.
5. **Highest Rates of Positive Tests-** this is the number of tests that came back positive for every 100 tests that were performed. This was calculated using the following formula: **(Total cases / Total tests) * 100**

## Limitations and Disclaimer
This dataset does not contain information about when this data was collected, or the source of the data for verification. However, this is fine because, this is a fictitious dataset for demonstration purposes, as stated earlier, and the figures and projected insights are not to be used for real world decision making.
