#Description: Chi Square Test
##Goodness of fit test, X square distribution, Test for Independence, Multiple Test

###Source: Galvanize Statistic Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Categorical, Continuous,
###DataTypes: Direct Code, API
###Model: Chi Square, Test for Independence
###Math: Chi Square Test, Chi Square Distribution, Test for independence, T statistics, Hypothesis Testing, Multiple Hypothesis Testing, Bonferroni Correction, FDR Correction, optimization 
###Subject: Quant, Science
###Transformations: covariance matrix, confusion matrix, bonferroni correction, FDR correction, optimization of confusion matrix
###Visualizations: Degrees of Freedom for distribution
###CodingNotes: 
###Library: pandas, statsmodels.api, python.display import latx YouTubeVideo, scipy import stats, 
###Library: statmodels.graphics.gofplots import qqplot, statsmodels.distributinos.empirical_distributions import ECDF
###Library: ipy_table import *,ipy_table import *

##More Details:
###X Square is similar to variance in that the observation is subtracted by expected and squared over expected in stead of n or N of DF
###8 degrees of freedom is where you get a flatter cutve, 1 degree of freedom or k value is parabolic
###Storing and plotting T values and P values. T is for similarity and p is for significance