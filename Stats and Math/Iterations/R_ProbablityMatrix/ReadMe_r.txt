#Description: Frequencies of games one by home and away team are plotted in a matrix based off of run total
##Much like a pivot table, win percentage based on proportion of runs from home and away team show how 
##Scoring is associated witha a given outcome and therefore predictives. 
##Runs are expected for home and away and given that expectation what is the probability that they will win

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