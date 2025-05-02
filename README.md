# Medical Insurance Cost Prediction Using Linear Regression

This project predicts medical insurance costs based on various features such as age, sex, BMI, number of children, smoking status, and region using Linear Regression.

## 🧠 Project Objective

The goal is to develop a machine learning model that can accurately estimate the medical insurance charges a person might incur, helping insurance companies and individuals plan better.

## 📂 Dataset

The dataset contains the following features:

- **age**: Age of primary beneficiary
- **sex**: Gender of the person (male/female)
- **bmi**: Body Mass Index
- **children**: Number of children/dependents
- **smoker**: Smoking status (yes/no)
- **region**: Residential region in the US (northeast, southeast, southwest, northwest)
- **charges**: Individual medical costs billed by health insurance

Sample data preview:

| age | sex   | bmi   | children | smoker | region    | charges     |
|-----|-------|--------|----------|--------|-----------|-------------|
| 19  | female | 27.9  | 0        | yes    | southwest | 16884.92    |
| 18  | male   | 33.77 | 1        | no     | southeast | 1725.55     |

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (for model building)

## 📊 Methodology

1. **Data Cleaning & Preprocessing**
   - Handled categorical variables using one-hot encoding.
   - Normalized numeric features if necessary.
2. **Model Building**
   - Applied Linear Regression to predict the `charges` column.
   - Evaluated model using metrics like Mean Squared Error and R² score.
3. **Visualization**
   - Correlation heatmaps and regression line plots to understand data patterns.

## 📈 Results

The linear regression model was trained and evaluated successfully. Although linear regression is a simple model, it gave a reasonable performance for this dataset. Advanced models can be explored for improvement.

## 🚀 Future Work

- Implement advanced regression models (e.g., Random Forest, Gradient Boosting).
- Add feature engineering (e.g., BMI category bins, interaction terms).
- Deploy the model using Flask or Streamlit for real-time predictions.


