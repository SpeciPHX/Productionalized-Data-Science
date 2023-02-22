#Description: Traditional Conjoint Analysis
##Analysis of attributes associated with smart phone marketing by brand, value, feature, price, convienence, attribute, A/B Testing

###CodeType: Python (Jueper)
###Data: Nominal, Categorical
###Model: Conjoint Analysis, OLS Multiple Regression, Attribute Importance, A/B Testing
###Math: OLS Regression, Descriptive
###Discipline: Marketing, Sales
###Transformations: Nominal transformation by summing nominal values
###Visualizations: OLS Regression Output, 
###CodingNotes:
###Library: Future, Pandas, Numpy, statsmodels.api, statsmodels.formula.api, pasty.contrasts impurt sum

##More Details:
###Multiple Regression uses ranking as the continuous variable. 
###Ranking is not defined. 
###Main effect model specifications on multiple regressional analysis of nominal data using sum function from pasty.contrasts
###The importance an attribute has over price per brand is determined on an A/B testing methodology and relative strength from reggressive analysis