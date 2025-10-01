# Loan-approval-prediction
This project predicts whether a loan will be approved or not

## Project Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Outlier detection and treatment
   - Encoded categorical variables
   - Scaled numerical features (StandardScaler, RobustScaler, PowerTransformer)

2. **Class Imbalance Handling**
   - Loan approval dataset was imbalanced (≈ 77% : 23%)
   - Applied **Oversampling (SMOTE)** on training data to balance classes

3. **Model Training**
   - Trained multiple models:
     - K-Nearest Neighbors (KNN)
     - Decision Tree (DT)
     - Support Vector Machine (SVM)
     - Naive Bayes (NB)
     - Logistic Regression (LR)
     - Random Forest (RF)

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
   - Cross-validation to check overfitting/underfitting



## ✅ Final Conclusion
- **Random Forest** performed the best with highest accuracy and F1-score.


Mehak Imran

Computer Science Student | AI & ML Enthusiast
