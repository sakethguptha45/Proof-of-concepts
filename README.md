# Proof-of-concepts
Degree of Seperation: The degree of seperation refers to the number of steps/connections required to link one entitiy to another in the network. The degree of freedom is used tell us the how tight/loosed packed a network is. There is a famous six degrees of freedom.

# It is the Section where there are tests to check the correlation between the different type of variables like (Continuous,Dichotomous(Binary),Categorical, Ordinal, Nominal, Finite, Infinite, Interval, Ratio )
# Point-Biserial Method: 
It is the special case of the pearson-Correlation method where one variable is dichotomous and other is Continuous. This is used to find the linear relationship between the two variables.
 The point-biserial values is in between the -1 and 1. 
A value of +1 indicates a perfect positive relationship: when the binary variable is 1, the continuous variable tends to have higher values compared to when the binary variable is 0.
A value of -1 indicates a perfect negative relationship: when the binary variable is 1, the continuous variable tends to have lower values.
A value near 0 indicates little or no linear association.

# P-value (p_val_pb):

# What It Is:
The p-value is the probability of obtaining a correlation coefficient as extreme as (or more extreme than) the one observed, under the null hypothesis that there is no linear relationship between the variables (i.e., the true correlation is 0).
# Range:
It ranges from 0 to 1.
A small p-value (typically below 0.05) suggests that the observed correlation is statistically significant, meaning it is unlikely to have occurred by chance.
A large p-value indicates that the observed correlation could be due to random variation, so you fail to reject the null hypothesis.

# T-test: 

# t-Statistic
# Definition:
It is the ratio of the difference between the group means to the standard error of the difference.

# Range:
- infinity to + infinity

A large positive t-statistic means that the mean of group_yes is much higher than the mean of group_no.
A large negative t-statistic means the opposite.
A t-statistic near 0 means the group means are very similar relative to the variability within groups.
# P-Value
Definition:
The p-value tells you the probability of obtaining a t-statistic as extreme as the one observed, assuming that the null hypothesis is true.
# Range:
The p-value ranges from 0 to 1.
Small p-value (e.g., < 0.05): Indicates that the observed difference is unlikely to be due to chance, so you reject the null hypothesis.
Large p-value: Suggests that the observed difference could easily be due to random chance, so you fail to reject the null hypothesis.
