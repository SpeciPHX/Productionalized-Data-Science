#Description: Comparing X square to Bayes for Hypothesis Testing with Minimal Data
## Bayes works better with minimal data but X square reaches the same solution with infinite samples

###Source: Galvanize Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Discrete
###DataTypes: Code Generated, From Library
###Model: Chi Square, Baysian, Hypothesis Testing
###Math: Chi Square, Baysian, Beta Distributions, Hypothesis Testing
###Subject: Science, Marketing, Management, Quant, Sales
###Transformations: Death and Survival Frequencies
###Visualizations: Chi Square vs Baysian given sample size, table of Chi Square and p value of Bayes
###CodingNotes:
###Library: numpy, pandas, matplotlib.pyplot, scipy.stats import beta, chisquare

##More Details:
###Threshhold is set at 52% survival after examining entire population
###Believed to be a 50% survival rate from low sample size prior to study
###Bayes gets a 95% confidence at 146 Trials
###Chi Square gets 95% confidence at 1398 Trials
