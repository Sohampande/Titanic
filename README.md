## Titanic Survival Prediction (Machine Learning Project)

This project predicts passenger survival on the Titanic using machine learning models built with Python and scikit-learn.

 Overview
This notebook demonstrates data preprocessing, feature engineering, model training, and evaluation using ensemble methods such as Random Forest, AdaBoost, Gradient Boosting, and XGBoost.

 Tech Stack
- Language: Python  
- Libraries: pandas, NumPy, matplotlib, seaborn, scikit-learn
- Tools: Jupyter Notebook  

 Features
- Data cleaning and imputation  
- Feature encoding using `OneHotEncoder` and `SimpleImputer`  
- Pipelines with `ColumnTransformer`  
- Model comparison with `GridSearchCV`  
- Evaluation metrics and visualization  

Model Performance
| Model             | Accuracy  |
|-------------------|-----------|
| Random Forest     | 0.76      |
| Gradient Boosting | 0.75      |
| AdaBoost          | 0.72      | 
| XGBoost           | 0.76      |

How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/<your-username>/titanic-ml-project.git
   cd titanic-ml-project
