# PID-diabetes_prediction
In this project, the onset of diabetes has been predicted. 
Increased accuracy have been obtained by using an ensemble of three feature selection methods which are Chi-Square Test, Mutual Information and ReliefF. 
This is because one filter might end up eliminating an important feature, which in why there are other filters which would preserve them.
Since most disease datasets are huge in dimension, an automatic diagnosis process through computing devices becomes complex and time-consuming. 
Feature selection methods can be used to eliminate unnecessary information from a dataset.

Sets of different ranking lists with corresponding filter-based rankers(here 3 such rankers shown) have been created.
The subset of best features is then taken and its union has been obtained. 
After obtaining the union of the best subsets of features, classification algorithms have been applied.
The number of features for which maximum accuracy is obtained (n), is then selected. 
We have varied the values of n, and in order to check the accuracy of the model, we have used three classifiers – Random Forest Classifier (RNF), NB and KNN.

The outcomes obtained from this work have successfully met the objectives of maximizing predictive performance, 
including all the prime features which a single filter method might have missed but at the same time also removing the redundant features. 
The least ranked features by the ensemble are the ones which have least importance in the dataset in terms of information, dependence as well as distance. 
Thus, MIRFCS also provides the information about the noisy, redundant or unnecessary features which are then discarded. 
Furthermore, selection of best set of features reduces the time consumed for analysis. 
All the three diseases which have been studied in this work are incurable but if diagnosed in time, can be controlled. 
This system can do that with the diagnosis time being minimum, treatment starting at the earliest, lesser attributes meaning lesser tests, hence economically benefiting for the patients.
