# Statistical Modeling: Workplace Safety Analysis

## Summary
This was a coursework assignment to introduce us in applying generalised linear modelling to count data in a real industry scenerio. The analysis was conducted to investigate and assess the company's workplace safety practices. 

**Key highlights:**
- Diagnosed and addressed overdispersion by moving from Poisson to Negative Binomial regression
- Conducted thorough model diagnostics (DHARMa residuals, Pearson/deviance residuals)
- Used stepwise selection (AIC) to identify significant predictors
- Provided data-driven recommendations with uncertainty quantification

### Dataset
72 observations of workplace groups with injury counts and variables: Safety regime, 
Experience level, Hours worked, Bonus rate, Training completion, and University degrees.

### What's Included
- Data processing & cleaning (handling missing values, identifying anomalies)
- Exploratory data analysis with visualizations
- Poisson and Negative Binomial model comparison
- Rigorous model diagnostics and goodness-of-fit testing
- Actionable recommendations based on statistical evidence

### How to Run
```R
rmarkdown::render("analysis.Rmd")
```
### Skills Demonstrated
- Detected overdispersion in Poisson model (17.94x expected variance), and subsequently
  switched to Negative Binomial and validated improved fit
- Statistical testing and validation
- Clear communication of technical findings to non-technical stakeholders
- Reproducible analysis in R/Rmarkdown
