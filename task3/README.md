# Task 3: Customer Churn Prediction

## Project Overview
Implemented a machine learning solution to predict customer churn in a telecommunications company using logistic regression.

## Objectives
1. Predict which customers are likely to stop using the service
2. Identify key factors influencing customer churn
3. Provide insights for customer retention strategies

## Implementation Details
### Data Preprocessing
1. Handled missing values in TotalCharges
2. Removed unnecessary features (customerID)
3. Encoded categorical variables using LabelEncoder
4. Prepared features for machine learning

### Model Development
1. Split data into training (80%) and testing (20%) sets
2. Implemented Logistic Regression classifier
3. Trained model with stratified sampling
4. Evaluated model performance using multiple metrics

### Key Features Analyzed
- Contract type
- Monthly charges
- Total charges
- Tenure
- Additional services
- Payment method

## Results & Insights
- Model Accuracy: ~80%
- Identified key churn indicators:
  - Contract type (month-to-month vs long-term)
  - Monthly charges
  - Tenure length
- Created visual representations:
  - Confusion matrix
  - Feature importance analysis

## Technical Stack
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Running the Analysis
1. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Run the Jupyter notebook
3. Review model performance and visualizations

## Dataset
Telco Customer Churn dataset containing:
- Customer demographics
- Service subscriptions
- Account information
- Churn status

## Business Impact
This model helps identify at-risk customers, enabling proactive retention measures and improved customer satisfaction.
