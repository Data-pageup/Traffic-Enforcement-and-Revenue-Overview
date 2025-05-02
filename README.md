# Medical Insurance Cost Prediction Using Random Forest Regressor

This project uses a **Random Forest Regressor** to predict medical insurance charges based on features like age, sex, BMI, smoking status, and region. The model significantly improves prediction accuracy compared to basic linear models.

## 🧠 Project Objective

To develop a machine learning model that predicts individual medical insurance costs using demographic and health-related features, which can assist insurance providers and policyholders in cost planning.

## 📂 Dataset

The dataset includes the following features:

- **age**: Age of the insured
- **sex**: Gender (male/female)
- **bmi**: Body Mass Index
- **children**: Number of dependents covered
- **smoker**: Smoking status (yes/no)
- **region**: U.S. region (northeast, southeast, southwest, northwest)
- **charges**: Medical insurance cost

Sample data:

| age | sex   | bmi   | children | smoker | region    | charges     |
|-----|-------|--------|----------|--------|-----------|-------------|
| 19  | female | 27.9  | 0        | yes    | southwest | 16884.92    |
| 18  | male   | 33.77 | 1        | no     | southeast | 1725.55     |

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- OneHotEncoder
- RandomForestRegressor
- Matplotlib / Seaborn (optional for visualization)

## 📊 Methodology

1. **Preprocessing**
   - One-hot encode categorical variables: `sex`, `smoker`, `region`
   - Concatenate encoded columns with numerical features

2. **Model Building**
   - Train/test split (80/20)
   - Model: `RandomForestRegressor(n_estimators=100, random_state=42)`

3. **Model Evaluation**
   - **Training R² Score**: 0.977
   - **Test R² Score**: 0.838
   - These results show the model fits well with minimal overfitting.

## 🚀 Future Work

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Try advanced models like XGBoost or CatBoost
- Visualize feature importance for better interpretability
- Deploy as a web app using Streamlit or Flask


