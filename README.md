# Job Satisfaction Analysis

This project performs an independent-sample T-test to determine whether the average levels of job satisfaction between full-time (FT) and part-time (PT) employees are the same or not.

## Problem

The problem is to determine whether there is a significant difference in job satisfaction between full-time and part-time employees.

## Data

The data used in this project is sourced from the [Stack Overflow 2018 Developer Survey](https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey) available on Kaggle. The survey data contains responses from over 60,000 developers worldwide. The data includes various demographic information, as well as responses to multiple questions about job satisfaction.

## Methods

The project uses the Shapiro-Wilk test to check the normality of the data, and the Levene's test for homogeneity of variances. It then performs an independent-sample T-test to compare the means of job satisfaction between the two groups.

## Results

The results of the Shapiro-Wilk test indicate that the data is normally distributed. The Levene's test shows that the variances of the two groups are not significantly different. The T-test shows that there is no significant difference in the average job satisfaction between full-time and part-time employees.

## How to Run

To run this project, clone the repository and run the R script. Make sure to have the necessary packages installed.
