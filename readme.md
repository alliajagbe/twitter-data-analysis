# Twitter Data Analysis

## Summary

Randomized Generation of Tweets with Data Analysis and Visualization

## Solution

I generated 100,000 data points randomizing the number of likes, retweets and comments each tweet had. I predefined the tweet categories ranging from sports and politics to health and science among six others. With this, I had sufficient data for analysis. This amount of data formed a representative unit of the live Twitter data as it was unbiased and followed a random distribution. 

## Approach 

I transformed the data into a data frame using the pandas library and probed into it further for data analysis. I then checked for the correlation between likes, comments and retweets. Based on this, I visualized the data for all three and noticed that they followed a very similar pattern as illustrated by the Kernel Density Estimator. I then made boxplots for the different categories as well in order to visualize the variability across them. 
