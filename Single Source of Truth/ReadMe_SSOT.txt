
#Single Source of Truth Searchable ReadMe
##Lots of spacing so please scroll down...
Single Source of Truth








#Description: Association Rule Basket Analysis of Categorical Data with Antecedent and consequenct support
##
py_Association_Rule_Basket
###Source: Syracuse
###CodeType: Python (Jupyter Notebook)
###Data: Categorical, Date/Time, Nominal, geogrphic, continuous
###DataTypes: HTTP Source, CSV Format
###Model: Association Rule, Basket Analysis, Apriori
###Math: Descriptive, Summary, Association Rule, Basket Analysis, Apriori, lift, confidence, antecedent support, consequent support, leverage, conviction
###Subject: Marketing, Sales, Management, Economic, Business Intelligence
###Transformations: Binning, Making Data Categorical, creating baskets, creating rules, 
###Visualizations: Bar Plot
###CodingNotes:
###Library: pandas, mlxtend, mlxtend.frequent_patterns import apriori association rule, seaborn, matplotlib.pyplot

##More Details:
###Virtually all of the business is in the UK and therefore data is more representative of UK until taken out
###










#Description: Baysian A/B Testing, Hypothesis Testing, Blob Analysis, Confidence Intervals of PDF
##
py_Bayes_AB_Confidence_Blob
###Source: Galvanize Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Boolian
###DataTypes: Direct Code, NPV
###Model: Baysian A/B Testing, Hypothesis Testing, Blob Analysis, Confidence Interval of PDF
###Math: Baysian, A/B Testing, Hypothesis Analysis, Posterior Distribution, Beta Distributions, Blob Analysis, Confidence Interval of PDF
###Subject: Marketing, Sales, Quant, Science
###Transformations: Beta Distributions, Probability Density PDF, Blob Analysis
###Visualizations: Beta Distributions, PDF Diagrams, Blob Analysis, Confidence Interval of PDF
###CodingNotes:
###Library: numpy, scipy, matplotlib.pyplot, plt.style.use('ggplot')

##More Details:
###Blob analysis uses normalized dataframe to plot random values. If the random values are above the X,Y slope
###generated by PDF. If the bolob is above the x,y slope, then random values are more correlated with PDF1 than PDF2












#Description: Bayesian A/B Testing and Conjugate Priors
##Prior Distribution, Liklihood Function, Posterior Distribution, Conjugate Priors, 
##A/B Testing, Frequentist vs Bayesian A/B Testing, Click Through Rate
py_Bayes_AB_Likilihood
###Source: Galvanize Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Discrete, Boolian, Categorical, Binomial
###DataTypes: Direct Code, Library
###Model: Bayse, A/B Testing, Hypothesis Testing, Likelihood, Probability Density, 
###Model: Joint Probability Density
###Math: Bayes, Bayes A/B Testing, Hypothesis Testing, Posterior Porbability, Liklihood, 
###MAth: Conjugate Priors, Probability Density PDF, 
###Math: Joint Porbability Density, Pareto, Percentage Away Probability Density
###MAth: Prior Distribution, Prior Probability Distribution, 
###Math: Bernoulli p value, Beta Distribution, Poisson Distribution, 
###Subject: Marketing, Sales, Quant, Science
###Transformations: Coin Fareness from Unifiorm Prior, Click Through Rate to Bayesian, 
###Perameter Shaping, Joint Probability Density, Normalized,  
###Visualizations: PDF vs R, Joint PDF, A/B Testing of Click Through Frequencies, 
###CodingNotes: Lots of cool figures and Normalization techniques
###Library: Matplotlib.pyplot, numpy, random, scipy import stat, bayes import bayes, 
###Library: plt.style.use('ggplot'), pltrcParams.update({'font.size: 14})

##More Details:
###posterior(????)???likelihood(????;????)??prior(????)
###Likelihood			Conjugate Prior
###Bernoulli/Binomial		Beta distribution
###Normal with known  ????		Normal distribution
###Poisson				Gamma
###Uniform				Pareto
###Recall Bayes' Theorem
###????(????|????)=????(????|????)????(????)????(????)
###When we use it in the context of statistics, we talk about the probability that a hypothesis  ????????
### is true given some observed sample  ????
###????(???????? | ????)=????(???? | ????????)????(????????)????(????)











#Description: Baysian A/B Testing for Conversion Rate
##Hypothesis Testing, Show A/B Testing for Conversion Rate is Baysian, Explain Conjugate Priors, Probability Density
py_Bayes_AB_Test_Conversion
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








py_Bayes_Cheat_Sheat_Chain
Bayes Equation Sheet










#Description: Comparing X square to Bayes for Hypothesis Testing with Minimal Data
## Bayes works better with minimal data but X square reaches the same solution with infinite samples
py_Bayesian_VS_Chi-Square
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









#Description: Bias in Variance Multiple Linear and Multinomial Regression Models
##Factors associated with housing prices
py_Bias_In_Variance_Regressi
###Source: Galvanize Resource
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Categorical
###DataTypes: Python Import
###Model: Bias in Variance, Multiple Linear Regression, Multiple Multinomial Regression
###Math: Regression, Multiple Linear, Multiple Multinomial, Descriptive, Summar, Linear Algebra, 
###Subject: Marketing, Realestate, Quant, Sales, Business Intelligence, Management, Science
###Transformations: plotting probabilities in conditional formatting for house size vs price, 
###Visualizations: Plotting Probability, multiple scatter, multiple regression, multinomial regression
###CodingNotes:
###Library: numpy, matplotlib.pyplot, matplotlib, scipy,

##More Details:
### All multiple regressions show an increase of price vs increase of house size when done linearly
### Multiple Multinomial regression shows a negative correlation for increase in price vs increase in house size










#Description: Central Limit Theorem
##
py_Binning_Means_SkewedData
###CodeType: Python (Jupyter Notebook)
###Data: continuous, multinomial, Normalized
###DataTypes: python package
###Model: Central Tendency from Normalizing Sample values to Sample means and distributing sample means
###Math: Central Limit Theorem, Descriptive, Summary. Standard Error of Mean, Normalization
###Subject: Economics, Marketing, Science, 
###Transformations: Sampling Distributions of Means, plotting distribution of means of random data, binning, Normalize
###Visualizations: Histograms of distribution of sample means
###CodingNotes: Pretty basic stuff, some functions
###Library: pandas, scipy, 

##More Details:
###Pretty straight forward stuff










#Description: Central Limit Theorem Comparing Histogram to Poisson and Binomial Distributions
##
py_Central_Limit_Histogram
###Source: Galvanize Stat Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, 
###DataTypes: Direct Code
###Model: N/A
###Math: Central Tendency, Poisson Distribution, Histogram, Binomial
###Subject: Quant
###Transformations: For Loop Where i is an if statement parameter
###Visualizations: Random Data, Histogram with Poisson Distribution or Binomial Distribution
###CodingNotes: N/A
###Library: numpy, seaborn, scipy

##More Details:
###There is no context to this data 
###From now on "Subject:" with no contexts will be known as Quant










#Description: Covariance, Summary Stats, and Central indicators
##py_Central_Loc_Covariance
py_Central_Loc_Covariance
###CodeType: Python (Jupyter Notebook)
###Data: continuous, bivariate
###DataTypes: N/A
###Model: Covariance
###Math: Mean, Covariance, Median, spread, bivariate association and dependence
###Subject: Science, Fundimentals, Descriptive, Summary
###Transformations: N/A
###Visualizations: N/A
###CodingNotes: Very straight forward, Fundimentals
###Library: N/A

##More Details:
###There is no context to the data analysis











#Description: Cheat Sheat of Continuous Probability, Two Variable Comparisons, Point Estimation
##
py_Cheat_Sheet_Point_Est
###Source: Galbanize Stats Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, 
###DataTypes: Direct Code
###Model: Covariance, Confustion Matrix
###Math: Covariance, Descriptive, Summary, Hypothesis Testing, Confusiton Matrix
###Subject: Quant, Science
###Transformations: Confusion Matrix
###Visualizations:N/A, Equation Sheet
###CodingNotes: This is largely an equation sheet that can be used to manually enter code following the equation
###Library: math import sqrt, 

##More Details:
###Mostly an equation sheet with a lot of subjects











#Description: Chi Square Test
##Goodness of fit test, X square distribution, Test for Independence, Multiple Test
py_Chi_Square_Multi_Hypoth
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











#Description: Confidence Intervals, T Distribution, T and Z score Retrevial per confidence interval
##
py_Confidence_Interval
###Source: Galvanize Stats Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Binomial, 
###DataTypes: Direct Code
###Model: Confidence Interval
###Math: Hypothesis Testing, T Distribution, Normal Distribution, Confidence Interval, t values
###Subject: Science, Quant
###Transformations: N/A
###Visualizations: N/A
###CodingNotes: Most of the code is acquiring z scores from a normal disctribution by plugging in confidence
###Library: scipy, numpy, scipy.stats import t, 

##More Details:
###Constant use of Z score of 1.96 for 95% confidence
###T score of 1.66 represents 95% confidence in T Distributions for 100-1=99 df









#Description: Confusion Matrix
##
Py_Confusion_Matrix_Basic
###Source: Galvinize Statistic Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Norminal
###DataTypes: Python Library
###Model: Confusion Matrix
###Math: Confusion Matrix
###Subject: Quant, Science
###Transformations: pd.crosstab from two boolian conditions gathering frequencies for confusion matrix
###Visualizations: Confusion Matrix
###CodingNotes: Nice Lambda statment
###Library: random import randint, pandas, numpy, 

##More Details:
### 1 = have car have kid, 2 = have car no kid, 3= nor car no kid, 4= no car have kid











#Description: Traditional Conjoint Analysis
##Analysis of attributes associated with smart phone marketing by brand, value, feature, price, convienence, attribute, A/B Testing
Py_ConjointAnalysis_Regre
###CodeType: Python (Jueper)
###Data: Nominal, Categorical
###DataType: CSV
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












#Description: Traditional Conjoint Analysis
##Analysis of attributes associated with smart phone marketing by brand, value, feature, price, convienence, attribute, A/B Testing
Py_ConjointAnalysis_Regre
###CodeType: Python (Jueper)
###Data: Nominal, Categorical
###DataType: CSV
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











#Description: Craps Function
##
py_Craps_Function
###Source: Galvanize Stats Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Discrete
###DataTypes: Direct Code
###Model: Frequencies, Functions
###Math: Descriptive, Summary, Frequency, Random Sample
###Subject: Gambling
###Transformations: Nested Functions, 
###Visualizations: N/A
###CodingNotes: If Statement with Nested While Loop, 
###Library:random, pandas, numpy

##More Details:
###Simple function to play out craps probabilities
###Might be a good idea to use these function to create frequencies of winning and losing










#Description: Response Correlation Multiple Logistic Regression Tuples and Setting Variables Exploritory Analysis
##Exploritory analysis on categorical data associated with responses and demographics using multiple regression and multiple logistic regression
py_Explor_Multi_Log_Reg
###Source: Syracuse
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Nominal, Categorical
###DataTypes: CSV
###Model:Multiple Regression, Multiple Logistic Regression, Logit
###Math: Summar, Descriptive, Regression, Multiple Regression, Logistic Regression, 
###Subject: Sales, Marketing, Business Intelligence
###Transformations: Setting Variables, Replacing Nulls, Cleaning, Correlation Matrix, 
###Visualizations: Histogram, Box Plot, customer response to switch conditioned by age, Swarm, Violin
###CodingNotes: Third Line is Great for setting variables and data cleaning
###Library: pandas, numpy, matplotlib.pyplot, statsmodels.api, statsmodels.formula.api, pasty, seaborn, evaluate_Classifier

##More Details:
###










#Description: Regressive Analysis on nominal, categorical, boolian, and continuous data to determine correlation of attributes to attendance
##What are the factors that influence attendence in a major league game using regression and business intelligence practices
Py_Exporatory_Descriptive
###CodeType: Python (Jupyter)
###Data: Nominal, Ordinal, Discrete, Boolian
###DataTypes: CSV, API
###Model: OLS Multiple Regression
###Math: Descriptive, Business Intelligence, pivot table, exploritory analysis
###Subject: Marketing, Sales, Business Intelligence
###Transformations: Ordering String Days of the Week and Month, 
###Visualizations: Box and Whiskers, OLS Regression Print Out
###CodingNotes: Train and Test data split before regression, days of the week and month ordered without time series analysis
###Library: __Future__, Builtins, Pandas, Maplotlib.pyplot, numpy, scipy.stats, statsmodels.api, statsmodels.formula.api

##More Details:
### Turns out that bobble heads have more of an impact on sales than fire works 
###Tuesday, Saturday, and Sunday are big selling days











#Description: Random Grades
##
py_Grades_Random_Sample
###Source: Galvanize Stats Lecture
###CodeType: Python (Jupyter Notebook)
###Data: integer, continuous, 
###DataTypes: random int generation
###Model: N/A
###Math: Arithmatic
###Subject: Quant
###Transformations: Binning, functions, nested if statement, nested functions
###Visualizations: N/A
###CodingNotes: nested functions with dependencies
###Library:

##More Details:
###









#Description: Euclidian Cluster Analysis with Continuous Variables and Dendrogram of Phylogeny and Hiearchy
##Used on random data points and clusterd into three centroids. 
py_Hierar_Clust_Dendro
###Source: Galvinize
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Hiearchical, Phlyogenic
###DataTypes: Direct Import, Random Sample
###Model: Cluster Analysis, Euclidian, Dendrogram, Phylogeny, Hiearchy
###Math: Cluster Analysis, Dendrogram, Tree, Phylogeny, Segmentation
###Subject: Matketing, Sales, Business Intell, Quant, Science
###Transformations: Normalization, Phlogenization, 
###Visualizations: Scatter Plot, Dendrogram
###CodingNotes:
###Library: numpy, scipy, pandas, sklear.datasets import make_blobs, scipy.spactial.distance import pdlist square form, scipy.cluster.hierarchy import linkage dendrogram, matplotlib.pyplot

##More Details:
### Hiearchy of clusterd values with a centroid of 3, creates dendogram of phylogeny or hiearchy, segmentation










#Description: Hypothesis Testing Binomial Inference Confidence How Many Iterations Before Statistically Significant
##
py_Hypo_T_Inference
###Source: Galvinize Statistic Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Discrete
###DataTypes: Code Generated
###Model: Hypothesis Testing
###Math: p value, t values, test statistic, binomial, binomial distribution, inference, confidence, frequencies
###Subject: Quant, Sports, Science
###Transformations: binomial, number of trials plotting out p values until significance
###Visualizations: multiple p values plotted out
###CodingNotes:
###Library: scipy, sympy import Eq S init_printing, sympy.stats import Binomial Die p density sample sample_iter
###Library: scipy import t binom stats ttest_1samp

##More Details:
### How many times can someone lose in something before they are certainly a loser
### How many trials until you have significance In[29]









#Description: K Means with automated seading and visualization of K and Kmean score
##
py_kMeans_Centoid_Opt
###Source: Galvinize DSI
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Phylogenic, 
###DataTypes: Parameters plotted
###Model: kMeans, kMean score
###Math: kMeans, Cluster Analysis, k mean score, RSS vs K, Sihouette vs k
###Subject: Marketing, Sales, Business Intelligence, Science, Quant, Management, 
###Transformations: RSS vs K, Sihouette vs k, 
###Visualizations: kMeans Clusters with relavant distributions from clusters
###CodingNotes: There was no Dendrogram created for phylogenic purposes
###Library: matplotlib.pyplot, numpy, sklearn.datasets import make_blobs, sklearn.cluster import KMeans, sklearn.metrics import silhouette_score, helper import cluster_and_plot

##More Details:
###Two clusters has the highest kmean score, 4 clusters also seems obvious but 8 and 7 kind of create a greater distinction of subgenre









#Description: Liklihood
##Statisical Inference Overview, Likelihood, Log-Likelihood, Maximum likelhood Estimation (MLE), Bayesian
py_Likelihood_Inference
###Source: Galvanize Statistic Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Discrete, Binomial
###DataTypes: Random, Direct in code
###Model: Inference, Likelihood Maximization (MLE), probability mass function, log likelihood, 
###Math: Inference, Likelhood, Log Likelihood, Maximizing Likelihood, binomial, binomial distribution, probability mass function
###Subject: Quant, Science, Operations, Sales, Marketing, Business Intelligence
###Transformations: Binomial, plotting p values, probability mass function, 
###Visualizations: Binomial Distribution, Centroid of most likely p values, probability mass function, 
###CodingNotes: N/A
###Library: scipy.stats import binom,  

##More Details:
###What is the likelihood of flipping a head 8 times and adjusting the stats p value to better fit reality of new likelihood









#Description: Moving Average Models and ARMA
## 
py_Moving_Average_Arima
###CodeType: Python (Jupyter Notebook)
###Data: Time Series, polynomials
###DataTypes: Python Import
###Model: Moving Average, Arima, Autocorrelation
###Math: Moving Average, Arima, Autocorrelation, Partial Autocorrelation Function (PACF)
###Subject: Finance, Economics, Marketing, Sales, Operations
###Transformations: functions
###Visualizations: autocorrelation, partial autocorrelation
###CodingNotes: Pretty straight forward
###Library: Pandas, Seaborn, statsmodels.graphics.tsaplots, statsmodels.tsa.arima_proces

##More Details:
###Basically just a raw example. Not a lot of context needed. 









#Description: Moving Average Models and ARMA
##
py_Moving_Average_ARMA
###Source: Galivinize Statistics Lecture 
###CodeType: Python (Jupyter Notebook)
###Data: Time Series
###DataTypes: Code Generated Random Seeding
###Model:Moving Averages, ARMA, Auto Correlation
###Math: Moving Average, ARMA, Auto Correlation, 
###Subject: Finance, Economics, Marketing, Sales, Operations, Science, Quant
###Transformations: random sample plotted over time series
###Visualizations: autocorrelation, partial autocorrelation 
###CodingNotes:
###Library: pandas, seaborn, statsmodels.graphics.tsaplots import plot_acf plotpacf, statsmodels.tsa.arima_process import arma_generate_sample

##More Details:
###









#Description:
##
Py_Plotting_TImeSeries_CSV
###CodeType: Python (Jupyter)
###Data: Time Series
###DataType: CSV, multiple CSV
###Model: Time Series Analysis
###Math: Eye Test
###Subject: Finance, Economics
###Transformations: Various time intervals, multiple visualizations
###Visualizations: Time Series Visualization either single or multiple images
###CodingNotes: Arima would be nice but it would need to be updated. Look at the R example for better forecasting and visualization
###Library: Panadas, datetime, matplotlib.pyplot, ARIMA, grangercausalitytests 

##More Details:
### Mostly here for formatting data that is time series for visualizations and eventual better use of the ARIMA library now that it has been updated with new terminology
### Economic data includes unemployment, durable goods, unemployment, consumer sentiment











#Description: Predictive, likelihood of winning a certain dollar amount randomly from possible prize
##How many would they need to buy before landing any combination of 3 total $50s or $100
py_Predictive_Likely_Win
###Source: Galvanize Statsistics Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Categorical, continuous, nominal
###DataTypes: direct code
###Model: Likelihood of winning, predictive statistics, mean of simulations
###Math: predictive statistics, frequencies, likelihood, weighting probability
###Subject: gambling, marketing, sales, quant
###Transformations: functional dependency, mean of simulation
###Visualizations:N/A
###CodingNotes: Mean of simulation is pretty cool
###Library: numpy, itertools

##More Details:
###Most likely probability is the mean of simulations of random data
###Probability of $1 = 52%, probability of $100 = 0.1%, what is the probability of picking three
###Of the three, what are the liklihood of winning either $50 or $100 









#Description: Random Card Generating Function
##
py_Random_Card_Generating
###Source: Galvanize Statistic Lecture
###CodeType: Python (Jupyter Notebook
###Data: Catagorical, Nominal
###DataTypes: code entered
###Model: N/A
###Math: Probability
###Subject: Gambling, Quant
###Transformations: Assigning Nominal and Continuous data to categorical and nominal data, Random dealing
###Visualizations:N/A
###CodingNotes: Really nice function with one liner for loops
###Library: random import randint, pandas, numpy, itertools, itertools import *, numpy import random

##More Details:
###










#Description: Random Card Generating Function
##
py_Random_Card_Generating
###Source: Galvanize Statistic Lecture
###CodeType: Python (Jupyter Notebook
###Data: Catagorical, Nominal
###DataTypes: code entered
###Model: N/A
###Math: Probability
###Subject: Gambling, Quant
###Transformations: Assigning Nominal and Continuous data to categorical and nominal data, Random dealing
###Visualizations:N/A
###CodingNotes: Really nice function with one liner for loops
###Library: random import randint, pandas, numpy, itertools, itertools import *, numpy import random

##More Details:
###









#Description: Arima Forecasts on Economic and Financial Data Acquired Through API With Visuals Printed in PDF
##Time series analysis of economic data including public sentiment, unemployment, durable goods, etc. 
##From the Federal Reserve Bank via API to be used for Arima forecasts of live data
R_Arima_Forecast_TimeSeries
###CodeType: R (Not MarkDown)
###Data: Time Series
###DataType: API
###Model: Irima
###Math: Irima, Eye Test Analysis, Time Series Analysis
###Subject: Economic, Finance
###Transformations: Seasonality, Various Time Points Formating, Supper Imposing, Irima formatting
###Visualizations: Economic and Finance Time Series Visualization, PDF of economic_analysis_er_forecast_R, econoimic_analysis_mts_R, economic_time_series_indexed_R
###CodingNotes: Download all dependencies on library or package
###Library: forecast, quantmod, lubricate, latticeExtra, lmtest

##More Details:
###Economic Data from Federal Reserve Bank of St. Louis (FRED system)









#Description: Association Rule Mining of Nominal Grociery Data With PDF Print Out Association Visualizations
##A deep dive behind product placement of nominal, categorical, and phylogenic data 
##associated with grocery store items using association rule mining and basket analysis
R_BasketAnalysis
###CodeType: R (Not Markdown)
###Data: Nominal, Categorical, Phylogenic 
###DataType: JSON, XML
###Model: Association Rule Mining Using Basket Analysis
###Math: Association Rule, Descriptive, Phylogeny, Business Intelligence, Pivot Tables, Support, Confidence, Lift, Coverage
###Subject: Marketing, Sales, Business Intelligence
###Transformations: Binning, Baskets, Grouped Matrix Rules, 
###Visualizations: PDF of market_basket_rules, market_basket_final_item_support, market_basket_farmers_rules, market_basket_rules_matrix
###CodingNotes: suggest using the apriori package or library
###Library: arules, arelesViz, RColorBrewer

##More Details:
###Turns out a lot of people are into whole milk and sausage. 
###Individual products or porduct category was used for association rule mining purposes and various diagrams and matrix 
###For example the parent of Vegitable was associated with other high level grociery store items
###Conversly specific sausage meet is bought with other sausage meet for cross sale
###Used to place items in grociery store and mostly for cross sales and impulse buys








#Description: R_Cluster_TagLine_Sentiment
##
R_Cluster_TagLine_Sentiment
###CodeType: R (Not Markdown)
###Data: CSV, .R, txt
###DataTypes: Nominal, Words, Date, Time Series
###Model: Cluster Analysis using Cosine and Euclidean, Tree Phylogeny, Word Sentiment over Time Series and Years Clustered
###Math: Cluster Analysis, Descriptive, Vectorization, Word Frequencies
###Subject: Marketing, Sales, Business Intelligence, Communications, Public Relations, Productiond
###Transformations: Date and Time, Vectorization, Frequency, Similarity and Disimilarity Matrix, 
###Visualizations: Dendrogram, Word Sentiment Plotted Over Time Series, Histogram of Time Series, 
###	Plotting Cluster of years relative to projecting direction of word sentiment score
###CodingNotes: Disimilarity Matix needs some TLC, An actual word cloud would be a nice addition per year or aggregate
###Library: RXKCD, tm, wordcloud, RColorBrewer, proxy, stingr, grid, ggplot2, latticeExtra, cluster

##More Details:
###Every Movie in 2009 tag line: I can, I will! Live in a world where just love, life, and a man is never one story
###The Word World is starting to go out of favor in the late 2010s and beyond in taglines
###If you want a tag line for a movie, you can't go wrong describing love












#Description: Process Control Charts of Call Rate and Length on Hold using arbitrary thresholds and Optimization on phone operators for days and times
##Linear Algebra and Six Sigma come together to do analysis on .R Data types and use descriptive and prescriptive statistics when not optimizing operations
R_Operations_Optimization
###CodeType: R (not MarkDown), R Workspace
###Data: Nominal, Continuous, Categorical, Boolian, Date/Time, Time Series
###DataTypes: CSV, API, R Workspace, R Data, .R
###Model: Linear Algebra, Six Sigma, Optimization Analysis 
###Math: Descriptive, Prescriptive, Six Sigma, Pivot Tables, Business Intelligence, Vectorization, Optimization, Sparce Matrix, Optimization of time linear regressively from sparse matrix. 
###Subject: Operations, Economics, Business Intelligence, Management
###Transformations: Vectorization, Sparse Matrix, New Column for day of the week mapped in touple with ordered numbers associated with the dates, date string to date variables, average call per hour of day, 
###Visualizations: Process Control Charts for days of month, week, hrs in day for both call length and number of calls  
###CodingNotes: 
###Library: lubricate, grid, ggplot2, queueing, lpsolve

##More Details:
###Could use some conditional formatting on some of these call hour per day of week per hour of day in a given month or week... 
###Probably best to use Power BI or Tableau for the BI images
###Processes are way out of control by what appears to be an arbitrary standard rather than a formal six sigma out of control process
###The processes were out of control regardless
###Linear Algebra on Sparse Matrix using linear regressive techniques for optimization of out of control process











#Description: Frequencies of games one by home and away team are plotted in a matrix based off of run total
##Much like a pivot table, win percentage based on proportion of runs from home and away team show how 
##Scoring is associated witha a given outcome and therefore predictives. 
##Runs are expected for home and away and given that expectation what is the probability that they will win
R_ProbablityMatrix
###CodeType: R (not Markdown)
###Data: Continuous, Float
###DataTypes: text
###Model: Descriptive, Frequencies
###Math: Frequencies, Linear Algebra, Probability, Pivot table, Sonditional Formatting, Coocurrence
###Subject: Sports, Baseball, Business Intelligence, 
###Transformations: Probability Matrix, Conditional Formatting, Iterations
###Visualizations: Probaility Matrix of Likeliohood of Hits for Home and Away Games
###CodingNotes: Good example of conditional formatting of matrix data for probabilities
###Library: lattice

##More Details:
###Probabilities favor the home team particularly in extreme circumsances
###For example, if a team were to score 9 runs to 1 run, 
###the odds of the team with 9 runs is 98.1% Home and a 9-1 away runs to home runs occurs 1.9%
###Most even split is 6-5 runs in a game for either home or away advantage
###50% either way is split by equal proportions of home and away, (1,1), (5,5), (9,9) are all 1:1 ratios











#Description:
##What influences attendence at a Baseball Stadium
R_Regres_Normali_Resid_ANOVA
###CodeType: R (not markdown)
###DataFormat: CSV, http: Web Content, 
###DataType: Nominal, Continuous, Categorical, Discrete, Boolian
###Model: Regression, Pivot Table, Nominal Regression, Multiple Linear Regression, Anova of Ordinal Data, 
###Math: Descriptive, Arithmatic, Business Intelligence, Exploritory Analysis, Pearson Distributions, Pearson Residuals, Residuals vs Leverage, Residuals vs Fitted, Scale vs Location, Normal QQ normalization, 
###Subject: Sports, Business Intelligence, Marketing, Sales
###Transformations: Days of the week in correct order, whether a bobble head was bought on day of the week, Months in correct order, Data Splitting for Training and Testing Data, Random Seeding
###Visualizations: Pivot Table, Box and Whiskers, Nominal Scatter Plot, Linear Regression Scatter Plot for Training and Test Data with two data types regressed, Pearson Distribution of Ordinal Data with Residuals, Residuals vs Leverage, Residuals Vs Fitted, Scales vs Location, Normal QQ Normalization
###CodingNotes: Ordering Nominal Data, Random Sampling of Test and Train
###Library: Car (Linear Regression), lattice (graphics package)

##More Details
###It turns out that bobble heads have the highest indication of whether a game will be high attendence with three levels of significance. 
###Fireworks also seeem to influence attendence but was not analyzed by regression
###Sunday and Tuesday were known for having very significant influence on attendence. Saturday was also found to be significant
###The ordinal aspect of day of the week and month of the year also influences attendence according to ANOVA


