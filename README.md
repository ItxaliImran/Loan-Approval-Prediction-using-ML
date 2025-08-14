# Loan-Approval-Prediction-using-ML
Machine Learning project predicting loan approval status based on applicant financial and demographic data using KNN, Decision Tree, and Random Forest algorithms with feature engineering and model comparison.


## 📌 Project Overview
This project aims to predict whether a loan application will be approved based on historical applicant data. It uses multiple machine learning algorithms to identify patterns and improve decision-making for financial institutions. The dataset includes applicant income, loan amount, credit history, and demographic details.

## 🎯 Objectives
- Predict loan approval using historical data.
- Compare multiple ML algorithms (KNN, Decision Tree, Random Forest).
- Identify key factors influencing loan approval decisions.

## 📊 Dataset
The dataset contains:
- Applicant financial details (income, loan amount, loan term)
- Demographic information (gender, marital status, dependents, education, self-employment)
- Credit history and property area
- Target variable: `Loan_Status` (Y/N)

## 🔍 Methodology
1. **Data Preprocessing**:
   - Handle missing values
   - Encode categorical variables
   - Normalize numerical features
2. **Exploratory Data Analysis (EDA)**:
   - Visualize data distributions
   - Identify correlations
3. **Feature Engineering**:
   - Select important features
   - Create derived variables
4. **Model Training**:
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
5. **Evaluation**:
   - Accuracy
   - Precision & Recall
   - Model complexity and computational efficiency

## 📈 Results
| Model          | Accuracy | Precision | Recall |
|----------------|----------|-----------|--------|
| KNN            | 88.3%    | 0.82      | 0.95   |
| Decision Tree  | 89.6%    | 0.82      | 0.97   |
| Random Forest  | **90.1%**| 0.82      | 1.00   |

- **Best Model:** Random Forest – highest accuracy, strong precision & recall, and robustness against overfitting.

## 💡 Key Insights
- Credit history and applicant income are strong predictors of loan approval.
- Random Forest provides the best balance between accuracy and model robustness.
- Feature engineering significantly improved model performance.

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

## 🚀 Future Improvements
- Include additional applicant behavior data
- Apply ensemble methods beyond Random Forest
- Build a web-based loan approval prediction interface

## 👨‍💻 Author
**Ali Imran Azmat**  
Electrical Engineer | AI & Data Science Enthusiast  
[LinkedIn](#) | [GitHub](#)

---
