# KNNRegressor
Development of a KNNRegressor with K Fold Cross Validation and Automatic Model Selection

This project implements a K-Nearest Neighbors (KNN) Regressor from scratch, with an internal cross-validation mechanism to optimize the k parameter. The model is evaluated using the diabetes dataset from scikit-learn. Key features of the project include:

KNN regression using a KDTree for efficient neighbor lookup.
Custom cross-validation using the LFold class.
Internal cross-validation within the training data and external evaluation using a test set split.

The model's performance is evaluated using the Mean Squared Error (MSE), which is calculated for both the training and test sets. The evaluation also computes the standard error for the MSE.

The optimal value of k is determined based on the lowest test error, with a confidence interval shown for each value of k.
The model is evaluated on an unseen test set, providing a measure of its generalization ability.
