# KNN-Classification-Based-on-KD-Trees-Data-Structure

## Objective

KNN (K Nearest Neighbour) is the supervised Machine Learning Algorithm in which we try to classify the unseen test data based on the class labels of the trained data sets. 
We also utilize it to predict the class labels of the test data points. Unlike other supervised Machine learning algorithms, KNN does not have any Mapping function through 
which a classification algorithm tries to learn from the training set. Instead, it retains the information of the full training data Hence, called the Lazy Learning Approach. 
The prediction of the labels of the test data points happens at the Run-time.

This classification technique works on the minimum distance approach. The distance metric often used is the Euclidean distance. 
The algorithm tries to find out the nearest neighbour (s) in the entire training data set. The main part here is that the time taken for the prediction of the nearest neighbour 
takes a significant amount of time. Here, we propose an efficient data structure called KD-Trees to store the training data sets to improve search operations.
at a later stage, we will be concluding that KD-Trees can be used as a Data Structure in KNN Machine Learning Classification Algorithm to improve the search performance while
finding out the nearest neighbour(s).
