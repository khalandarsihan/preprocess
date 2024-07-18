# Project Title
 Data preprocess

## Initial Commit

### Notebook Details
- **Dataset Creation:**
  - Used `make_classification` from `sklearn.datasets` to create a synthetic dataset with 1000 samples, 20 features, 15 informative features, and 5 redundant features.
- **Data Splitting:**
  - Split the dataset into training and testing sets using `train_test_split` with a test size of 33% and a random state of 1.
- **Data Normalization:**
  - Applied `MinMaxScaler` from `sklearn.preprocessing` to normalize the data.
  - Fitted the scaler on the training data and transformed both the training and testing data.
- **Model Training:**
  - Trained a logistic regression model using `LogisticRegression` from `sklearn.linear_model`.
- **Model Evaluation:**
  - Evaluated the model's performance on the test data using `accuracy_score` from `sklearn.metrics`.
  - Printed the accuracy of the model.

### Included Files
- **Notebook:**
  - `binary_classification_of_synthetic_data.ipynb`
- **Images:**
  - `data_cleaning.png`
  - `data_transforms.png`
  - `data_variable_type.png`
  - `dimensionality_reduction.png`
  - `feature_selection.png`
- **.gitignore:**
  - Excludes virtual environments and temporary files:
    - `.venv/`
    - `.ipynb_checkpoints/`
    - `__pycache__/`
    - `*.pyc`

