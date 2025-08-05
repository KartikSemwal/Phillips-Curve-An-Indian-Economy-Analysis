## Phillips Curve: An Indian Economy Analysis (1991-2024)
This Project provides an in-depth analysis of the 'Phillips Curve' in the context of the Indian economy, focusing on the period from the economic reforms of 1991 up to 2024. The Phillips Curve, as described by A.W. Phillips, is the inverse relationship between Wage Inflation and Unemployment. Phillips conjectured that the lower the unemployment rate, the tighter the labor market and, therefore, the faster firms must raise wages to attract scarce labor. At higher rates of unemployment, the pressure abated.  

By investigating this relationship over three decades of transformative change in India, this project aims to reveal important trends, regime changes, and policy implications.

## Objectives:
* Empirical analysis of the relationship between Inflation and Unemployment in India from 1991–2024.
* Compare different time periods (e.g. pre- and post-2008 global crisis, pre- and post-pandemic) to observe shifts and shape of the Phillips Curve.
* Identify non-linearities or changes in slope (flattening/steepening) and potential causes.
* Estimation of  NAIRU.
* Discuss the policy relevance of the Phillips Curve for India’s central bank and government.

## Key steps and Methodologies:
**_1. Data Collection & Preprocessing:_**
* Source: Both the data, i.e, Inflation data(CPI based) and Unemployment data were taken from data.worldbank.org
* Both the data were cleaned and merged to get a single dataset.
* All datasets are available in the data/ folder with relevant documentation.

**_2.Exploratory Data Analysis:_**
* Plotted the Inflation and Unemployment line graphs using matplotlib to check the trend.
* Visualized the Phillips curve by plotting the Regression plot between Inflation and Unemplyment using seaborn.
* Calculated the r-value and p-value using linregress.
* Plotted phillips curve for four different time periods, to see the short term trends.
* Plotted bar chart to compare the average inflation and unemployment rates across those four periods in India.

**_3.Estimation of NAIRU:_**
* NAIRU was estimated using two methods:
  * Change in inflation on lagged unemployment method
  * Expectations-Augmented Phillips Curve Equation
