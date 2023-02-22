#Description: Bayesian A/B Testing and Conjugate Priors
##Prior Distribution, Liklihood Function, Posterior Distribution, Conjugate Priors, 
##A/B Testing, Frequentist vs Bayesian A/B Testing, Click Through Rate

###Source: Galvanize Lecture
###CodeType: Python (Jupyter Notebook)
###Data: Continuous, Discrete, Boolian, Categorical, Binomial
###DataTypes: Direct Code, Library
###Model: Bayse, A/B Testing, Hypothesis Testing, Likelihood, Probability Density, Joint Probability Density
###Math: Bayes, Bayes A/B Testing, Hypothesis Testing, Posterior Porbability, Liklihood, 
###MAth: Conjugate Priors, Probability Density PDF, Joint Porbability Density, Pareto, Percentage Away Probability Density
###MAth: Prior Distribution, Prior Probability Distribution, Bernoulli p value, Beta Distribution, Poisson Distribution, 
###Subject: Marketing, Sales, Quant, Science
###Transformations: Coin Fareness from Unifiorm Prior, Click Through Rate to Bayesian, Perameter Shaping, Joint Probability Density, Normalized,  
###Visualizations: PDF vs R, Joint PDF, A/B Testing of Click Through Frequencies, 
###CodingNotes: Lots of cool figures and Normalization techniques
###Library: Matplotlib.pyplot, numpy, random, scipy import stat, bayes import bayes, plt.style.use('ggplot'), pltrcParams.update({'font.size: 14})

##More Details:
###posterior(𝑝)∝likelihood(𝑝;𝑥)×prior(𝑝)
###Likelihood			Conjugate Prior
###Bernoulli/Binomial		Beta distribution
###Normal with known  𝜎		Normal distribution
###Poisson				Gamma
###Uniform				Pareto
###Recall Bayes' Theorem
###𝑃(𝐴|𝐵)=𝑃(𝐵|𝐴)𝑃(𝐴)𝑃(𝐵)
###When we use it in the context of statistics, we talk about the probability that a hypothesis  𝐻𝑖
### is true given some observed sample  𝑥
###𝑃(𝐻𝑖 | 𝑥)=𝑃(𝑥 | 𝐻𝑖)𝑃(𝐻𝑖)𝑃(𝑥)