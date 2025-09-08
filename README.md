# 🏠 Housing Prices Prediction (Kaggle Competition)

This repository contains my work for the [Housing Prices - Home Data for ML Course](https://www.kaggle.com/competitions/home-data-for-ml-course) Kaggle competition.  
The goal is to predict house prices based on various features using Machine Learning models, achieve **>90% accuracy**, and submit results to Kaggle.

---

## 📌 Project Workflow

1. **Data Loading**
   - Train & test data from Kaggle competition dataset.
   - Initial data exploration.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of target variable (`SalePrice`).
   - Correlation heatmap of features.
   - Identification of top features related to house prices.

3. **Data Preprocessing**
   - Handling missing values (median for numeric, mode for categorical).
   - Encoding categorical variables using One-Hot Encoding.
   - Feature scaling using `StandardScaler`.
   - Aligning train and test datasets for consistent feature space.

4. **Model Training**
   - Trained multiple models:
     - Linear Regression  
     - Ridge & Lasso Regression  
     - Random Forest Regressor  
     - Gradient Boosting Regressor  
     - XGBoost Regressor  
     - LightGBM Regressor  
     - CatBoost Regressor  

   - Evaluation metric: **R² Score** (via 5-Fold Cross Validation).

5. **Model Comparison**
   - Compared average cross-validation scores for all models.
   - Selected the best-performing models.

6. **Hyperparameter Tuning**
   - Used `GridSearchCV` for Random Forest (and could extend to other models).
   - Tuned parameters like `n_estimators`, `max_depth`, and `min_samples_split`.

7. **Final Model & Submission**
   - Trained the tuned best model on the entire training set.
   - Predicted house prices for the Kaggle test dataset.
   - Generated `submission.csv` for Kaggle submission.

---

## Visualizations

<img width="975" height="544" alt="Image" src="https://github.com/user-attachments/assets/2f99c7a8-b0d2-45e8-9009-302d2a39d7dc" />
<img width="723" height="569" alt="Image" src="https://github.com/user-attachments/assets/b4ab45f3-4bff-40ff-a9d0-fa54ec114d8f" />
<img width="766" height="646" alt="Image" src="https://github.com/user-attachments/assets/0f5504fa-0180-42fa-a139-60dde0599ceb" />
<img width="378" height="83" alt="Image" src="https://github.com/user-attachments/assets/22738d1a-3cb8-45e9-96fb-efc0a65435a2" />
<img width="769" height="193" alt="Image" src="https://github.com/user-attachments/assets/ab64e0ae-181c-41bd-bd08-40e630a6981d" />
<img width="641" height="222" alt="Image" src="https://github.com/user-attachments/assets/eef87686-1ae0-4c1d-b43a-b4fc41337c17" />
<img width="945" height="247" alt="Image" src="https://github.com/user-attachments/assets/23140a81-9451-4251-b114-4894b744ec88" />

## 📊 Results

- Compared multiple models and recorded their **R² scores**.
- Achieved more than **90% accuracy** after tuning.
- Generated a valid Kaggle submission file.

---

## 📂 Profile

- [LinkedIn](https://www.linkedin.com/in/sadikujjaman)
- [Kaggle Profile](https://www.kaggle.com/code/mdsadikujjamanshihab)

