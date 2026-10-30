# House Price Prediction Using Machine Learning

## Project Overview
This project predicts house sale prices using Machine Learning techniques. The project uses the House Prices - Advanced Regression Techniques dataset from Kaggle.

## Competition Details
- **Platform:** Kaggle
- **Competition:** House Prices - Advanced Regression Techniques
- **Competition Link:** https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
- **Submission Status:** Successfully submitted
- **Kaggle Score:** 0.14412

## Dataset
The dataset contains information about residential properties.

- Training data: 1,460 rows and 81 columns
- Testing data: 1,459 rows and 80 columns
- Target variable: SalePrice

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Kaggle

## Methodology
1. Load training and testing datasets.
2. Separate input features and target variable.
3. Handle missing numerical values using median imputation.
4. Handle missing categorical values using most-frequent imputation.
5. Apply One-Hot Encoding to categorical variables.
6. Train a Random Forest Regression model.
7. Predict house prices for the test dataset.
8. Generate the submission CSV file.
9. Submit predictions to the Kaggle competition.

## Model Used
**Random Forest Regression**

The model uses 500 decision trees and a random state of 42.

## Competition Result
- Submission file: `submission_kaggle.csv`
- Submission status: Successful
- Kaggle score: **0.14412**
- Evaluation metric: Root Mean Squared Logarithmic Error (RMSLE)

A lower RMSLE score indicates better prediction performance.

## Project Files
- `House_Price_Prediction_Kaggle.ipynb` – Python notebook containing the competition implementation.
- `submission_kaggle.csv` – Predicted house prices submitted to Kaggle.
- `House_Price_Prediction(ML).ipynb` – Original project notebook.

## Conclusion
This project provided practical experience in data preprocessing, feature encoding, Random Forest Regression, prediction, and Kaggle competition submission. The model successfully generated predictions and achieved a Kaggle score of 0.14412.

## Author
Shruti Pande
