#Description: Bayesian A/B Testing and Conjugate Priors
##Prior Distribution, Liklihood Function, Posterior Distribution, Conjugate Priors, 
##A/B Testing, Frequentist vs Bayesian A/B Testing, Click Through Rate

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
###posterior(π)βlikelihood(π;π₯)Γprior(π)
###Likelihood			Conjugate Prior
###Bernoulli/Binomial		Beta distribution
###Normal with known  π		Normal distribution
###Poisson				Gamma
###Uniform				Pareto
###Recall Bayes' Theorem
###π(π΄|π΅)=π(π΅|π΄)π(π΄)π(π΅)
###When we use it in the context of statistics, we talk about the probability that a hypothesis  π»π
### is true given some observed sample  π₯
###π(π»π | π₯)=π(π₯ | π»π)π(π»π)π(π₯)