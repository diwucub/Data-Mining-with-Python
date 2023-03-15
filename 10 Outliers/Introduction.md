Outlier detection, also known as anomaly detection, is a technique used to identify observations in a dataset that deviate significantly from the majority of the data. These observations are often referred to as "outliers" or "anomalies." Outlier detection is useful in a variety of fields such as finance, healthcare, and cybersecurity, for identifying unusual patterns, fraud, or errors in data.

There are many different Outlier Detection methods we use with Scikit-Learn, but some of the most common include:

Isolation Forest: A method that isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature.

Local Outlier Factor (LOF): A method that calculates the local density of a data point and compares it with the densities of its neighbors. Data points with a low local density are considered outliers.

One-class SVM: A method that learns a boundary that separates the majority of the data from the outlier data.

DBSCAN: is a density-based clustering algorithm that can be used for outlier detection. DBSCAN groups together data points that are close to each other based on a density threshold, called Eps, and a minimum number of points, called MinPts. Data points that are not part of any dense group are considered outliers.

IQR: is a statistical measure that can be used to detect outliers in a dataset. It is defined as the difference between the third quartile (Q3) and the first quartile (Q1) of a dataset. The IQR is a measure of the spread of the middle 50\% of the data, and it is robust to outliers.
