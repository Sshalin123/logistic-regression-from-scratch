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


# when building from scrtch(for goated ppl only)

### Data Loading and Preprocessing:
first load the Iris dataset directly from its URL and name the columns.
The dataset is filtered to only include two classes ("Iris-setosa" and "Iris-versicolor"), and only two features (sepal length and sepal width) are selected.
Class labels are converted to binary (0 or 1).
Features are normalized to have zero mean and unit variance.
### Logistic Regression Implementation:
The class LogisticRegressionScratch implements the logistic regression model using gradient descent.
The sigmoid function computes the probability estimate.
The fit method performs gradient descent updates and tracks the loss (binary cross-entropy) at each iteration.
The predict_prob and predict methods compute probability estimates and binary predictions, respectively.
### Training and Visualization:
The model is trained for 1000 iterations with a learning rate of 0.1.
Training accuracy is printed, and the loss over iterations is plotted to show convergence.

