# Task 4: Customer Churn Model Comparison

## Project Overview
Implemented and compared multiple machine learning models for customer churn prediction to identify the most effective approach.

## Key Objectives
1. Compare different ML algorithms for churn prediction
2. Evaluate model performance using multiple metrics
3. Identify the most reliable model for deployment

## Implementation Details

### Data Preprocessing
1. Cleaned and standardized input features
2. Handled missing values in TotalCharges
3. Encoded categorical variables
4. Scaled numerical features

### Models Implemented
1. **Logistic Regression (Baseline)**
   - Simple linear approach
   - Easily interpretable results
   - Baseline for comparison

2. **Random Forest**
   - Ensemble learning method
   - Handles non-linear relationships
   - Built-in feature importance

3. **XGBoost**
   - Advanced gradient boosting
   - High performance
   - Robust to overfitting

### Evaluation Metrics
- Accuracy Score
- Classification Report
  - Precision
  - Recall
  - F1-Score
- Confusion Matrix

## Results
1. **Comparison of Model Performance**
   - Accuracy scores
   - Precision-Recall trade-offs
   - Confusion matrix analysis

2. **Key Findings**
   - XGBoost generally performed best
   - Random Forest showed good balance
   - Logistic Regression provided baseline

## Technical Stack
- Python 3.x
- scikit-learn
- XGBoost
- pandas
- numpy
- matplotlib
- seaborn

## Running the Analysis
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn
   ```
2. Run the Jupyter notebook
3. Compare model performances

## Dataset
Telco Customer Churn dataset with:
- Customer demographics
- Service subscriptions
- Account information
- Churn status

## Business Impact
- Identified most reliable model for churn prediction
- Provided comparative analysis for model selection
- Enabled data-driven decision making for model deployment
