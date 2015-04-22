# Statistical_Inference
This repository contains files submitted in completion of the Statistical Inference course, which is one of nine courses from the data science specialization offered by Johns Hopkins University's Department of Biostatistics on coursera.org

## Course Project

### Part 1
In this section of the project I investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda. Lambda = 0.2 for all of the simulations. Then I investigate the distribution of averages of 40 exponentials with a thousand simulations.

The report illustrates via simulation the properties of the distribution of the mean of 40 exponentials in order to 

1. Compare the sample mean and the theoretical mean of the distribution.

2. Compare the sample variance and the theoretical variance of the distribution.

3. Show that the distribution is approximately normal.

### Part 2
This section of the project is focused on data from R's ToothGrowth dataset found in the datasets package.

The markdown file begins with a summary of the data.  Then continues with an exploratory plot and 3 hypothesis tests looking at the effect of Vitamin C on the growth of ginea pig teeth adminstered in two different ways: orange juice and ascorbic acid.