# KNearestNeighbours

KNN can be used for both classification and regression predictive problems. However, it is more widely used in classification problems in the industry.


We can implement a KNN model by following the below steps:

Load the data
Initialise the value of k
For getting the predicted class, iterate from 1 to total number of training data points
Calculate the distance between test data and each row of training data. Here we will use Euclidean distance as our distance metric since it’s the most popular method. The other metrics that can be used are Chebyshev, cosine, etc.
Sort the calculated distances in ascending order based on distance values
Get top k rows from the sorted array
Get the most frequent class of these rows
Return the predicted class


Choosing the value of K is mportant. -> Look into the code for choosing value of K


KNN is impacted if our data set is imbalanced
KNN is impacted if our data set has outliers

Hence:
Rescale data
Handle missing data
choose data with low dimensionality
