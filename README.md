# Data_Analytics_Wine_Quality_Assignment
Assignment - 1
Dataset Description:
The wine data set consist of total 1599 tuples. Training dataset consist of 1119 tuples and testing dataset consist of 480 tuples. Total number of attributes are 12. 
Implement the following tasks:
1)	Linear regression to detect/estimate the value of “quality” attributes of a wine in the dataset.
Input: Training dataset and testing dataset
Output: Graphical representation of fitting a line over your training data and sum of square error calculation for test dataset.
2)	Use the following classifier to detect the quality of wine. As all the attributes of the data sets have numerical values you can take “quality” attribute of the dataset as class label. In Quality attribute the values greater than or equal to 7 can be considered as “good “ quality and the quality value less than 7 can be considered as “bad” quality. So now you have two class problem.
a.	Logistic Regression
b.	Linear Regression as a classifier
c.	SVM
d.	Naïve Bayesian
3)	Compare all the classifier based on Accuracy, Precision, Recall, F-measure, Sensitivity, and Specificity and discuss the result
Input: Test results from task 2
Output: values of each measures with respect to each classifiers
4)	Find the correlation between attributes and apply PCA (Discuss about the correlation with respect to wine dataset). While applying PCA leave attribute “quality” as it is. So you have total 11 attributes. All the classifiers (a to d) should be applied again over the newly constructed dataset (dataset constructed using PCA) for the following number of attributes and evaluated using measures given in (3)
a.	7 (i.e. from PCA we get 11 attribute so take first 7 attributes of the newly constructed dataset, call this dataset as redwine_7_training and redwine_7_testing)
b.	4 (i.e. from PCA we get 11 attribute so take first 4 attributes of the newly constructed dataset, call this dataset as redwine_4_training and redwine_4_testing)
Input: {redwine_7_training and redwine_7_testing, redwine_4_training and redwine_4_testing}
Output: values of each measures with respect to each classifiers and each dataset (both redwine_7 and redwine_4)

So what do you observe when taking 7 attribute and when you are taking 4 attributes what impact does the dimensionality have in various classifiers (based on evaluation measures).



Note: While using PCA for construction of new data from the existing data, PCA should be applied over both training and testing data.
