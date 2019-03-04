---
output:
  html_document: default
  pdf_document: default
---
![](logos/CRUK_CI_logo.png)![](logos/LMB_logo_small.png)
## Linear Modelling with R Course Cheatsheet
  
| **ANOVA**.  | Notes  |
| --- | --- |
| aov()  | linear model with categorical predictors  |
| oneway.test() | (heteroscedastic) linear model with a categorical predictor  |
| kruskal.test  |  rank-based linear model with a categorical predictor |
| t.test()  | (heteroscedastic and heteroscedastic) linear model with a binary predictor  |
| tapply()  | apply a function to each vector element  |
| qqnorm()  | normal quantile-quantile plot   |
| shapiro.test()  | test of normality  |
| bartlett.test() | test of equality of variance between groups  |

| **Simple Regression**  | Notes |  
| --- | --- |
| cor()  | correlation between between 2 variables |   
| cor.test()  |  test for (linear or rank) association between 2 variables |   
| residuals()  | extract residuals from a model fit  | 
| lm()  | linear model fit |

| **Multiple Regression**  | Notes  |
| --- | --- |
| AIC()  | Akaike's information criterion for a fitted model  |
| stepAIC()  | AIC based stepwise model selection |
| nls()  | non-linear least squares |

| **Generalised Linear Models**  | Notes  |
| --- | --- |
| install.packages()  | blah  |
| glm()  | generalised linear model fit  |
| gamlss()  | generalised linear and additive model fit  |
| anova()  | comparison of embedded models  |
| chisq.test()  | Pearson's chi-square test  |
| prop.test()  | test of equality of proportions |

| **Time Series and Non-Linear Models**  | Notes  |
| --- | --- |
| acf()  | auto-correlation function  |
| pacf()  | partial auto-correlation function  |
| arima()  | ARIMA Modelling of time series  |
  




