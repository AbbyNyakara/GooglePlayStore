Preparing data for exploration is considered the dirty work in data analysis
In this notebook, i cleaned the data by first removing the outliers. 
I used a boxplot to see the distribution of the data and to pinpoint where the outliers are likely to lie. 
I then used the percentile method to set the maximum threshold to remove the outlier. 
I then cleaned the data further by replacing the null values with the medium for the Rating column(Because it was right_skewed)
For the categorical data, i used the mode for the null values. 
I then changed the type of some columns to numerical data to give more data for exploration purposes. 
