# SVM Classification Practice 
## Problem definition and motivation:
solving a multi-class classification problem in which is an important task in many fields such as image recognition, text analysis or bioinformatics. we want to compare the performance of different kernels and regularizations for the Support Vector Machine (SVM) algorithm 
## Dataset: 
6 datasets, Each dataset has two features and six classes,Tuples come in different shapes and densities, such as aggregates, concatenations, spirals, flames, jain, and paths.  
## Approach and methodology: 
using SVM algorithm, trying to find the optimal hyperplane to separate data points into classes vary with maximum margin. 
### Data pre-processing: 
we use Standard Scaler to scale the features to get zero unit mean and variance, which can improve the performance and stability of the SVM algorithm. 
### Model selection: 
using three different kernels for the SVM algorithm: linear, polynomial, and radial basis functions (RBF) and two different regularization values for the SVM algorithm: 0.1 and 100. Lower values allow more flexibility and higher values will prevent overfitting. 
### Model training: 
using the SVC class to create and adapt an SVM classifier to the given kernel and regularization values. 
### Model evaluation: 
using the accuracy_score function to calculate the accuracy of the SVM classifier on the test set. we also use the plot_decision_region function of the mlxtend 
library to plot the SVM classifier's decision boundaries on the scaled data, along with titles and legends. 
## Implementation: attached with the report 
## Conclusion:  
• successfully applied the SVM algorithm to the multi-class classification problem on 6 synthetic data sets 
• compared the performance of different kernels and regularization values for the SVM algorithm 
• visualized the decision boundaries of the classifiers.  
• learned how to use the scikit-learn and mlxtend libraries in Python to implement and evaluate SVM algorithms.  
• learned how to scale objects, separate data, and save diagrams. 
