# Testing-the-Hypothesis-of-the-Normal-Distribution-of-Logarithmic-Returns-Using-the-Lilliefors-Criter
1. Introduction

 Many analytical calculations and methods in statistics
based on the normal distribution. In most cases
such criteria depend on the sample size. And that is why when
in a deliberately small sample size, the criterion is often not worth
be used, since the reliability of the results will be extremely low. At
the study of sufficiently large samples, the criteria are always
quite accurately can give an answer about the normality of its distribution, which is widely used in practice. Purpose of the work: confirmation of the hypothesis that the logarithmic the profitability of shares of companies in the period 04/04/2011-04/04/2021 did not distributed normally.

Work tasks:
a) Checking the performance of the Lilliefors criterion on model
data.
b) Analysis for the normality of the logarithmic stock returns
companies based on the Lilliefors criterion.
Research methods: Lilliefors test for analysis
the normality of the distribution of the logarithmic stock returns
companies. The Kolmogorov-Smirnov criterion was also used
to assess the uniformity of the distribution of P-values ​​of statistics
Lilliefors on the interval [0;1].
Object of study: data of companies included in the S&P 500 index for
2012 - 2021 inclusive. Stock quotes of these tickers
have undergone significant changes due to the pandemic,
thereby confirming their relevance. There are 10 data in total
tickers for 10 years.

2. Theoretical part

a) P-value of the test
Of particular interest is the P-value of the statistical test,
which is denoted as PV x1,…,xn and represents
the maximum (largest) level of significance at which
the hypothesis H0 is still accepted.
c) Lilliefors criterion (main)
The Lilliefors test is a statistical test that is
modified Kolmogorov-Smirnov (Kolmogorov) criterion,
used to test the normality of a distribution. Their difference is
what is the mean and variance, the parameters are normal
distributions are not known in advance, and for the normal law we take
parameters that are directly calculated from the sample.
In other words, if the P-value has already been found, then the question of deviation
hypothesis H0 is solved as follows:

 if PV <α, then H0 is rejected;
 if PV≥ α, then H0 is not rejected.
Also, one should take into account the fact that with the correct H0 P-value
distributed evenly over the interval from 0 to 1.
Classical Kolmogorov (Kolmogorov-Smirnov) criterion
used to test elementary hypotheses about conformity
analyzed sample and some completely known law
distribution.

b) Kolmogorov-Smirnov criterion (auxiliary)

In this work, the Kolmogorov-Smirnov criterion was chosen as
auxiliary for estimating the uniformity of a set of p-values.
The Kolmogorov criterion is a compliance criterion, so it is excellent
suitable for this task. Also, the choice is due to the fact that this criterion
more “general” and not as powerful as, for example, the Shapira-Wilk test.
This will have a positive effect on further analysis of real data, since,
judging by the term papers of previous years on the topic of checking the distribution of prices
stocks for normality, in most cases a negative result was obtained.
The "Lilliefors distribution" is the distribution of the test statistic with
fulfillment of the null hypothesis condition.
The hypothesis of a normal distribution is tested by the following method:

 Estimation of variance and sample mean;

 Find the largest deviation between the distribution functions
(theoretical and selective), as well as when working with the Kolmogorov criterion;

 A decision is made on the statistical significance of the observed
deviations of the sample distribution function from the theoretical one.

If the decision is positive, then the null hypothesis must be rejected.
Estimation of the parameters of the theoretical distribution is carried out according to the data
which are checked for compliance with the distribution, which is the main
the reason for the error of the Lilliefors criterion. From the above, it follows
that the maximum deviation will be less than the independent estimate
distribution parameters. That is why the probability distribution in
the assumption of the null hypothesis being true, or simply "the null
distribution" of the criterion statistics turns out to be shifted to smaller
values ​​when compared with the Kolmogorov distribution.
