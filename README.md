# 🌲 Forest Fire Index Prediction 
Using Regression Models on the Algerian Forest Fires Dataset

## 📌 Project Overview
This project focuses on predicting the Forest Weather Index (FWI) using various regression algorithms.
FWI is an important indicator used to assess fire danger levels based on meteorological conditions.
Using the Algerian Forest Fires dataset from Kaggle, the project explores data preprocessing, feature analysis, and multiple regression techniques to build an effective predictive model.

## 📂 Dataset
Source: Algerian Forest Fires Dataset (Kaggle)
The dataset contains meteorological and fire-related features collected from two regions in Algeria (Bejaia and Sidi Bel-Abbès).

##  🔑 Key Features
#### Temperature
#### Relative Humidity
#### Wind
#### Rain
#### FFMC, DMC, DC, ISI indices
Fire occurrence indicators

## 🛠️ Techniques & Algorithms Used
### 🔧 1. Feature Scaling / Standardization
StandardScaler applied to normalize numerical features
Ensures equal contribution of features to regression algorithms
### 📊 2. Box Plots for Outlier Analysis
Visualized the effect of StandardScaler
Identified distribution patterns and extreme values
### 🤖 3. Regression Models Implemented
#### ✔ Linear Regression
Baseline model to understand basic relationships
#### ✔ Lasso Regression
Performs L1 regularization
Helps in feature selection by shrinking coefficients
#### ✔ Cross-Validated Lasso
Evaluates performance across multiple folds
Selects the best alpha for Lasso
#### ✔ Ridge Regression
L2 regularization
Used to handle multicollinearity and stabilize coefficients
##### ✔ ElasticNet Regression
Combines L1 + L2 penalties
Balances sparsity and stability

## 🔍 Model Evaluation
All models were evaluated using metrics such as:
### 1. R² Score
### 2. Mean Squared Error (MSE)
### 3. Root Mean Squared Error (RMSE)
### 4. Cross-validation was used to ensure model robustness.

## 📈 Results Summary
### Standardization significantly improved model performance
### Regularization methods (Lasso, Ridge, ElasticNet) helped reduce overfitting
### Best model depends on parameter tuning (ElasticNet/LassoCV generally performed best)

## 📁 Project Structure
├── data/
│   └── Algerian_forest_fires_dataset.csv
├── notebooks/
│   └── forest_fwi_regression.ipynb
├── src/
│   └── preprocessing.py
│   └── models.py
│   └── evaluation.py
└── README.md

## 🚀 How to Run
### 1. Clone the repository
### 2. git clone <your-repo-link>
### 3. cd forest-weather-index
### 4. Install dependencies
### 5. pip install -r requirements.txt
### 6. Run the Jupyter Notebook or Python scripts
### 7. jupyter notebook

## 📌 Conclusion
This project demonstrates how regression techniques can be applied to environmental datasets to predict fire-related indices.
By using scaling, visualization, and multiple regression models, the final system gives strong predictive insights into forest fire risk levels.

## 🙌 Acknowledgements
### Dataset by Kaggle – Algerian Forest Fires Dataset
### Scikit-Learn for regression models
### Matplotlib & Seaborn for visualization
