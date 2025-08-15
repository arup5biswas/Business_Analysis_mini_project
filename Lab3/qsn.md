Datasets:
Adult income dataset: https://archive.ics.uci.edu/dataset/2/adult Estimate proportions (e.g., proportion of individuals earning more than $50,000) and means (e.g., average hours worked per week).


Programming Questions:
You are given a population dataset containing the ages of 10,000 individuals. The goal is to demonstrate the Central Limit Theorem (CLT) by taking multiple random samples from this dataset, calculating their means, and then plotting the distribution of these sample means.
Steps to follow: Sampling Distribution of the Sample Mean
CLT Animation: https://onlinestatbook.com/stat_sim/sampling_dist/
Load the dataset: You have a dataset ages.csv containing a single column age with 10,000 entries. Choose a continuous variable from the dataset. “Try with different distributions of the input data - need not be age”.
Take random samples: Write a function that takes a random sample of a specified size n from the population and returns the sample mean. You will use this function to draw multiple samples.
Calculate sample means: Using the function, draw 1,000 samples of size n = 50 from the dataset and calculate their means. Store these means in a list.
Visualize the distribution: Plot the histogram of the sample means. Overlay this histogram with a normal distribution curve using the mean and standard deviation of the sample means to show how the distribution approaches a normal distribution as described by the Central Limit Theorem.
Find mean, variance and standard deviation (standard error) of the sample mean distribution.
Find the confidence interval [l, r] that contains the true mean with probability 0.95. 
Bootstrapping:
Select only one sample (n=30), and obtain 1000 bootstrapping samples. Perform steps 4,5 and 6 provided in the above question.
Proportion:
Select one sample from a population and find the confidence interval for proportion and margin of error for proportion. “Refer to PDF document”  “0.95”

Bootstrapping: Bootstrapping is a resampling technique that involves repeatedly drawing samples, with replacement, from the observed data (i.e., the single sample collected). Each resample is of the same size as the original sample.
Purpose: The main purpose of bootstrapping is to estimate the sampling distribution of the sample mean (or any other statistic) without needing to make strict parametric assumptions about the population distribution.