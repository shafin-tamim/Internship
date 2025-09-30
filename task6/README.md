# Task 6: Sales Forecasting Using Time Series Analysis

## Project Overview
Developed a time series forecasting model to predict future sales using SARIMA (Seasonal ARIMA), enabling data-driven inventory management.

## Implementation Details

### 1. Data Preprocessing
- Converted dates to datetime format
- Aggregated daily sales data
- Handled missing values and resampled time series
- Created consistent daily frequency dataset

### 2. Time Series Analysis
- Performed stationarity test (Augmented Dickey-Fuller)
- Applied differencing for non-stationary data
- Analyzed seasonal patterns
- Split data into training and test sets

### 3. Model Development
- Implemented SARIMA model with parameters:
  - Order: (1,1,1)
  - Seasonal Order: (1,1,1,7)
  - Weekly seasonality consideration
- Trained model on historical sales data
- Generated 30-day sales forecast

### 4. Visualization & Evaluation
- Historical sales trends
- Test predictions with confidence intervals
- 30-day forecast projection
- Model performance metrics

## Results
- Generated accurate 30-day sales forecasts
- Identified seasonal patterns in sales data
- Provided confidence intervals for predictions
- Created visual representations of forecasts

## Technical Stack
- Python 3.x
- pandas: Data manipulation
- statsmodels: Time series modeling
- matplotlib/seaborn: Visualization
- scikit-learn: Model evaluation

## Key Features
1. Data Cleaning & Preprocessing
2. Stationarity Testing
3. SARIMA Model Implementation
4. Confidence Interval Calculation
5. Visual Result Presentation

## Business Impact
- Improved inventory management
- Better resource allocation
- Data-driven decision making
- Reduced stockout risks

## Running the Analysis
1. Install requirements:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
   ```
2. Run the Jupyter notebook
3. View forecasting results and visualizations
