# Zillow_Housing_Analysis


# Exploratory Data Analysis

This dataset contains a pleathora of infomation not relevant to the exploratory data analysis. It is better to concenrate on the data that gives more insight. Examining the Sales price distribution affords the oppotunity to see the outliers within the data and how the sales are skewed. Seperating the Salesprice will yeild a normal distribution for machine learning. 

# Numerical data distribution

It is imporant to plot all the data points in order to see the distibution. Identifying the data that correlates with the Salesprice can yeild valuable insight for machine learning. 

By looking at correlation between numerical values we discovered 11 features which have a strong relationship to a house price. Besides correlation we didn't find any notable pattern on the datas which are not correlated.

Notes:

There may be some patterns I wasn't able to identify due to my lack of expertise
Some values such as GarageCars -> SalePrice or Fireplaces -> SalePrice shows a particular pattern with verticals lines roughly meaning that they are discrete variables with a short range but I don't know if they need some sort of "special treatment".


# Principal Component Analysis for Dimensionality Reduction

PCA is used in exploratory data analysis and for making predictive models. The reduction of the dimensions of the data, yet preserve the variance for analysis. This is important in providing non-parametric analysis.

In this project, PCA is used to lessen the dimensionality of the data and signal the varaince for a predictive model on the Salesprice (Y) output. 
