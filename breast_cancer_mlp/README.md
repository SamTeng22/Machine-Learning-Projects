Breast Cancer Classifier using MLP (Neural Network)

This mini machine learning project uses the [breast cancer dataset]
(https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) 
from `scikit-learn` to build a neural network model using `MLPClassifier`.

Technologies:
- Python
- Jupyter Notebook
- scikit-learn

How it works:
1. Loads database from scikit-learn and other dependencies
2. Splits data to training and test sets with a ratio of 8:2
3. Scales the features with StandardScaler
4. Trains a neural network with MLPClassifier
5. Tuned hyperparameters with GridSearchCV
6. Evaluates the model using the test accuracy and classification report
