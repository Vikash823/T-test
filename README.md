T test in statistics:

Def: A t-test is a statistical test used to compare the means of two groups , generally applied when sample size is small and population variance is unknown.



Type:

1.One sample T test:

 Compares the mean of a single group to a known value or theoretical expectation.

2. Independent Two sample T test:

 Compares the means of two independent groups to see if they are significantly different.

3.Paired sample T test

Compares the means of two related groups.

e.g- comparing the blood pressure of patient before and after treatment



Assumptions:

1. The data should be approximately normally distributed.

2.The samples should be independent of each other (except for paired t-tests).

3.The variance in the two groups should be approximately equal. If not, a variation of the t-test (Welch's t-test) can be used.



Steps to Perform a T-Test:

1.State the Hypotheses:

Null Hypothesis (H₀): Assumes no difference between the means 

Alternative Hypothesis (H₁): Assumes there is a difference between the means.

2.Choose the Significance Level (α):

3.Calculate the Test Statistic:

using respective formulas/python

4.Determine the Degrees of Freedom(df) :

5.Compare the Test Statistic to the Critical Value:

Use a t-distribution table  to find the critical value for the given df and significance level α.

If the calculated t-statistic is greater than the critical value, reject the null hypothesis.

6.Interpret the Results:

Reject H₀: If the p-value is less than α, there is evidence to suggest a significant difference between the means.

Fail to Reject H₀: If the p-value is greater than α, there is not enough evidence to suggest a significant difference.

