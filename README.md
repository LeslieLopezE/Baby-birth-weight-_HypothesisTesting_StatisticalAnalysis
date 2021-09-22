# Baby birth weight_HypothesisTesting

This exercise analyses a dataset of baby birth weight to investigate the relationship between the variable "weight" and other variables using T-test where feasible. 
Does weight vary with other variables?

## Variables' Description

Variable ->	 Label

Weight ->	Infant birth weight


Black	-> Black Mother


Married	-> Married Mother


Boy	-> Baby Boy


MomAge	-> Mother’s Age


MomSmoke ->	 Smoking Mother


CigsPerDay	-> Cigarettes Per Day

MomWtGain	-> Mother’s Pregnancy Weight Gain

Visit	-> Prenatal Visit

MomEdLevel -> Mother’s Education Level

MomAge: The mothers were between the ages of 18 and 45. The MomAge variable is centered at the mean age, which is 27. 
Thus MomAge=-7 means the mother was 20 years old whereas MomAge=5 means that the mother was 32 years old.

## Findings and conclusions

### A baby’s weight is dependent on baby’s gender AND on mother’s color, marital or smoker status:

1. T-test results ran between dependent variable Weight and the following independent boolean variables confirm that we reject the Null Hypothesis -> H0:
u1=u2

2. We conclude that the samples came from populations with unequal variances (P value of Equality of Variance is 0.001% < Confidence Interval 5%). 

Thus, weight mean DOES vary depending on the following variables:

- Black

- Married

- MomSmoker

- Boy

3. The sample is normally distributed

## Limitations of the study

The relationship between Weight and bi-categorical independent variables CigsPerDay, MomWtGain, Visit, MomEdLevel must be evaluated using different statistical tests
