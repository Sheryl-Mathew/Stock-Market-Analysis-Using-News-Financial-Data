# Stock Market Analysis Using News Financial Data

We are in a world where data is increasing exponentially every second. News is one of the
biggest generators of data. The aim is to harness this news data along with the data that we
get from stock markets to predict stock price

## Data

The data is provided by the following sources:

Market data : Intrinio <br />
o It contains financial market information such as opening price, closing price,
trading volume, calculated returns.<br />

News data : Thomson Reuters<br />
o It contains information about news articles/alerts published about assets, such
as article details, sentiment, and other commentary.<br />

## Implementation

1.	Exploratory Data Analysis

Visualizing the data considering few features at each instance to figure out their role in the dataset. Plotting the different variables from the dataset also considering their frequency to check their relationship with the target variable. Some forms of EDA include histograms, barplots, ggplots, qplots. All the graphs that were generated while performing EDA have been included in the below section.   

2.	Feature Engineering

The process of extracting useful features is done through feature engineering. This is achieved by plotting histograms, frequency and density graphs after which they are analyzed and based on their interpretations features selected.

3.	Principal Component Analysis

Principal Component Analysis is a dimensionality reduction method which is used for feature extraction. This is done by combining the input variables in a specific manner and finding the most important variables so that we can drop the unimportant ones. All the variables after PCA are independent of each other. Example for PCA in deep learning is document image analysis.

4.  Regression Techniques

Linear Regression <br />
Random Forest Classifier<br />
Support Vector Regression<br />

