#Description: Baysian A/B Testing for Conversion Rate
##Hypothesis Testing, Show A/B Testing for Conversion Rate is Baysian, Explain Conjugate Priors, Probability Density

###Source: Galvanize Lectures
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Categorical, Boolian, Binomial
###DataTypes: Direct Code, NPZ, 
###Model: Baysian A/B Testing, Hypothesis Testing,
###Math: Baysian, A/B Testing, Hypothesis Testing, Beta Distributions, Conversion Rate, Probability Density PDF, Central Tendency
###Subject: Sales, Marketing, Quant, Science
###Transformations: Probability Densisty of Conversion Rate, Comparing Site C to A
###Visualizations: Probability Density vs Conversion Rate, Beta Distributions
###CodingNotes: NPZ is three boolian columns
###Library: numpy, scipy, matplotlib.pyplot, plt.style.use('ggplot')

##More Details:
### Mean of Beta Distribution alpha/(alpha+beta) - Creates a central tendency of beta distribution
### Alpha = 1 +number of conversions on our website
### Beta = 1 + number of misses on the website
### Site A and B compared to a new Site C