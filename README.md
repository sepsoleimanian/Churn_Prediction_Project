# 🛒 Churn Prediction Project | Pin-Dees (Zarrino)

This project aims to predict the probability of a user making their **fifth purchase** based on the behavior observed in their first four transactions. It is a binary classification problem focused on identifying potential churned retailers.

---

## 📂 Project Structure

| File/Folder | Description |
| :--- | :--- |
| **`order_history.csv`** | Original dataset containing transaction history for 200 users. |
| **`labels.csv`** | Target labels for 120 users (Loyal vs. Churn). |
| **`1_EDA_FeatureEng.ipynb`** | source code of EDA and Feature Engineering. |
| **`2_modeling_hyperparameter_hardcode.ipynb`** | source code of Modeling. |
| **`3_modeling_hyperparameter_GridSearchCV.ipynb`** | source code of Modeling using GridSearchCv for Hyper Parameter Tuning. |
| **`full_dataset.csv`** | Final dataset after Feature Engineering. |
| **`predictions_rf_only.csv`** | Final predictions using the tuned Random Forest model. |
| **`predictions_xgb_only.csv`** | Final predictions using the tuned XGBoost model. |
| **`Churn_Prediction_Project.pdf`** | Full project report with technical and business insights. |
| **`Churn_Prediction_Project.Doc`** | Same as `Churn_Prediction_Project.pdf` but in .doc format. |


---

## 🚀 How to Run
1. Ensure you have `pandas`, `seaborn`, `scikit-learn`, and `xgboost` installed.
2. Run the `.ipynb` notebooks to reproduce the features and model results.
3. The output predictions will be generated as `.csv` files in the root directory.
