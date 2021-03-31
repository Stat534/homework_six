HW 6
================

This is the second of a two - part homework. For HW 6, again use the
data from the [Johns Hopkins Covid-19
Dashboard](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data#usa-daily-state-reports-csse_covid_19_daily_reports_us).

``` r
covid_data <- read_csv('https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/03-27-2021.csv') 
```

Fit a spatial regression model to explain the `Incident_Rate` or you can
use a Poisson specification and include population. Additionally, feel
free to explore other covariates (such as mask mandates), but you will
have to do a little work finding and aggregating that info.

### Q1. (4 points)

Write out the mathematical framework for the model you are fitting.

### Q2. (6 points)

Fit the model and interpret all of the predictors. Include a discussion
about implications of the model predictors and spatial structure.

### Q3. (4 point)

Explain the need, or lack thereof, of including spatial structure in the
model.

### Q4. (1 point)

Include a research question and summary of data visualization for
project 2.
