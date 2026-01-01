# Credit Risk Classification using Machine Learning

This repository contains a machine learning project for classifying credit risk using **Logistic Regression** and **Support Vector Machine (SVM)** models. The project was completed as part of the CM4371 - Machine Learning & Pattern Recognition course.

## Dataset
- **File:** `credit_risk_synthetic.csv`
- **Description:** Synthetic dataset containing numerical and categorical features related to credit applications.
- **Target Variable:** `default` (indicates whether a client defaulted or not)
- **Categorical Columns:** `home_ownership`, `purpose`


## Methodology
1. **Data Loading & Exploration**
   - Loaded dataset using Pandas.
   - Examined structure, data types, and missing values.

2. **Preprocessing**
   - Encoded categorical variables using **Label Encoding**.
   - Checked for missing values.
   - Scaled features using **StandardScaler** (important for SVM).

3. **Model Training**
   - Split data into training and test sets (80/20 split).
   - Trained **Logistic Regression**.
   - Trained **Support Vector Machine** with a linear kernel.

4. **Evaluation**
   - Evaluated both models using **accuracy**.
   - Tested predictions on random unseen samples.

5. **Comparison**
   - Compared model accuracies to determine better performance.

## Results
| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 98.75%   |
| Support Vector Machine | 99.25%   |

**Observation:** The Support Vector Machine model achieved slightly higher accuracy, indicating better classification performance for this dataset.

## Usage
1. Open the Jupyter Notebook `credit-risk-classification-ml.ipynb`.
2. Ensure the dataset `credit_risk_synthetic.csv` is in the same folder.
3. Run the notebook cells in order.

## Requirements
- Python 3.x
- Pandas
- NumPy
- scikit-learn
- Jupyter Notebook / VS Code Jupyter extension

## License
This project is developed for academic purposes as part of the CM4371 course and is not intended for commercial use.
