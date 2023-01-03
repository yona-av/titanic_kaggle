# Titanic Kaggle Competition

This is an undescriptive overview of the process that I followed to get a prediction of the passengers who survived the Titanic disaster using Kaggel's titanic dataset.
More on the logic and the reasoning of the steps could be found in the [EDA notebook](https://github.com/yona-av/titanic_kaggle/blob/main/EDA_notebook.ipynb) and the [Project Code](https://github.com/yona-av/titanic_kaggle/blob/main/project_code.ipynb).

## EDA 
- Recognized missing values in the data set .
- Explored survival chances based on sex, age, fare, class, embarkation and familly size.


## Data processing 
- Filled Nan values in the needed columns.
- Eliminated features that doesn't have a statistical significance.
- Encoded the data by it's type, Categorical and Continous.



## ML model
- Tried few models to give a prediction : SVC, SGD, Logistic Regression, Random Forest, KNN and XGBoost.
- Did fine tuning of hyperparameters on SVC, the classifier that gave the best prediction accuracy on kaggle 0.8.
- Retrained the model without the hyperparameters  tuning after it gave a worse result 0.79.

