
**Hypothesis testing:**

H0 : The mean crime count is the same between rainy and non-rainy days. (in original study: Precipitation does not affect the daily violent crime count in Boston.)

HA : The mean crime count is not the same between rainy and non-rainy days. (in original study: The presence of precipitation decreases the daily violent crime count in Boston.)

According to these hypotheses, the treatment group for our experiment includes all days when there was precipitation (i.e. PRCP > 1) and the control group includes all days when there was no precipitation (i.e. PRCP = 0).

The variables we will analyze include crime levels, heat index, wind and heat index, PRCP values, snow levels, wind levels, seasons (winter and spring), and events.

The test statistic used in the original analysis was average exposure effect. We recreated this by subtracting the average crime rate per rainy day from the average crime rate per non rainy day in Boston. 

Overall it was found with the test statistic, bootstrap confidence interval, and data visualizations that more crimes occurred on days when it did not rain. The average crime rate for rainy days was 230 whereas the average crime rate for non rainy days was 239. 

Therefore we reject the null hypothesis. 
