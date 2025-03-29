# logistic-regression-from-scratch
logistic regression from scratch as well as  using scikit-learns built-in functions
so both of them are uploaded 

## steps I followed are as follows 

## Data Preparation:
The dataset is loaded, filtered for two classes, and two features (sepal_length and sepal_width) are selected. The class labels are converted to binary.

## Feature Normalization:
StandardScaler is used to scale the features to have a mean of 0 and standard deviation of 1.
this was done due to several perks :--
Equal Contribution: It ensures that no feature dominates the gradient descent process due to its scale, allowing all features to contribute equally.
Faster Convergence: Normalized features can improve the speed and stability of the optimization algorithm, helping gradient descent converge faster.
Numerical Stability: Scaling avoids issues with very large or small numbers, which can cause numerical instability in calculations.

## Model Training:
The LogisticRegression model from scikit-learn is created and trained using the normalized data.

## Evaluation/Laststep  :
Finally, the training accuracy is computed and printed.


