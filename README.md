# AB-Testing

A/B testing to compare the efficiency of two web pages to retain users. 

# Project purpose

In this project, we will be understanding the results of an A/B test to use statistics, 
regression, and other data analysis to help determine if the new page should be implemented, 
keep the old page, or perhaps run the experiment longer to make the decision.

# Tools used

Jupyter notebook (Python)

- Data cleaning and statistical analysis

# In repository

Data

Python program : Loading data and statistical analysis

# Data source

https://www.kaggle.com/datasets/feeldidaxie/landing-page-ab-testing-dataset

# Steps involved

1. Load data as dataframe.

2. Convert time data into seconds (0.01 => 1s).

3. Visualize data distribution using box plot.

4. Hypothesis testing (Shapiro Wilk test) : To determine if data is normally distributed.

5. Test equality of variance of the samples (Levene's test).

6. Test for statistically significant difference between the medians of samples (Mann-Whitney U test).

# Data distribution

<img width="849" height="543" alt="Image" src="https://github.com/user-attachments/assets/fe676546-ced0-4f3a-940c-3d8a66207363" />

# Conclusion

P-value of the given samples are greater than the significance of 0.05, which fails to reject the hypothesis: 

  There is no significant difference between the time spent by users on web page A and web page B.

This could be due to lack of sufficient data, so, the experiment should be continued with a much larger dataset.
