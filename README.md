# Heart Disease Prediction

This project aims to predict the likelihood of heart disease using machine learning models. The dataset used is the **Framingham Heart Study dataset**. The project applies data preprocessing, feature scaling, class balancing, and hyperparameter tuning to optimize model performance.

## Dataset
The dataset consists of multiple medical and lifestyle-related features, including:
- Age
- Sex
- Cholesterol levels
- Blood pressure
- Smoking habits
- Diabetes status
- BMI
- And more...

The target variable is **TenYearCHD**, indicating whether the patient is likely to develop coronary heart disease within 10 years.

## Libraries Used
- `pandas` - Data manipulation
- `numpy` - Numerical computations
- `seaborn` & `matplotlib` - Data visualization
- `scikit-learn` - Machine learning models & preprocessing
- `imbalanced-learn` - Handling class imbalance using SMOTE
- `xgboost` - Gradient boosting model

## Data Preprocessing
1. **Handling Missing Values**: Missing values are imputed using the mean strategy.
2. **Feature Engineering**: Columns are renamed and irrelevant columns are dropped.
3. **Feature Scaling**: StandardScaler is used to normalize the data.
4. **Class Balancing**: SMOTE (Synthetic Minority Over-sampling Technique) is applied to address class imbalance.
5. **Train-Test Split**: Data is split into training (70%) and testing (30%) sets.

## Models Implemented
- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**
  

## Model Evaluation
- **Accuracy Score**: Measures the overall correctness of predictions.
- **Classification Report**: Includes precision, recall, and F1-score.
- **Confusion Matrix**: Shows true positives, true negatives, false positives, and false negatives.
- **Accuracy Comparison Plot**: Displays model accuracy comparison using bar plots.


