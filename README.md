# Predicting Credit Card Payment Default Project
This GitHub repository will be used to host project files for Predicting Credit Card Payment Default using Ensemble Approach with Classifiers.

The goal of this project is to use **ensemble modeling approach with classifiers**. 

Ensemble modeling  is a process where multiple diverse models are created to predict an outcome, either by using many different  or using different training data sets. The ensemble model then aggregates the prediction of each base model and results in once final prediction for the unseen data.

## Analysis Approach
-   Using decision trees on a Dataset to make a prediction
-   Applying hyper-parameters tuning for decision trees by using RandomGrid
-   Using ensemble algorithms for predicting payment default.

## Algorithms Used For Ensemble Modeling

 - Random Forest 
 - Adaboost 
 - Extra trees classifier  
 - Gradient Boosted Tree

## Implementation at high level

 - Load the data set
 - Data Preprocessing
	 - Data Clean up
	 - Spitting Data into 2 sets : Training data and Test data 
 - Data Analysis
	 - Build a confusion matrix for decision tree classifier
	 - Hyper-parameter tuning
	 - Building decision tree by RandomGrid search over hyper-parameters
 - Build classifiers using Ensemble model and run the model
 - Learning curve
	 - Decision Tree 
	 - Random Forest Classifiers

## Conclusion

| Approach | Accuracy |
|--|--|
| Random search on decision tree | 82.73% |	
| Manual tuning of hyperparameters | 82.95% |	
| Random Forest Classifier | 82% |	
| AdaBoost Classifier | 82.68% |	
| Extra Trees Classifier | 80.66% |	
| Gradient Boosting Classifier | 82.8% |	
| Voting Classifier | 82.38% |	

With change in size of training data, the accuracy has gone down nearly 7%. This shows the model's sensitivity to data and its instability which again is a known weakness.
