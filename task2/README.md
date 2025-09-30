# Task 2: Interactive Retail Sales Dashboard

## Project Overview
Created an interactive dashboard to visualize key insights from the retail data analysis. The goal was to transform raw data into actionable business insights through an intuitive interface.

## Key Objectives
1. Transform complex data into digestible visualizations
2. Create an interactive user interface for data exploration
3. Present key business metrics in real-time
4. Enable data filtering by country and time period

## Implementation Details
### Data Preparation
- Loaded cleaned dataset from Task 1
- Processed datetime information for temporal analysis
- Calculated derived metrics (sales, hourly patterns)

### Dashboard Features
1. **Interactive Filters**
   - Country selector for market-specific analysis
   - Date range picker for temporal analysis

2. **Key Performance Indicators**
   - Total sales with currency formatting
   - Average order value calculation
   - Customer count tracking

3. **Dynamic Visualizations**
   - Monthly sales trends with line charts
   - Product performance with horizontal bar charts
   - Hourly sales patterns for shopping behavior analysis
   - Geographic sales distribution

## Technical Stack
- **Framework**: Dash by Plotly
- **Data Processing**: Pandas
- **Visualization**: Plotly Express
- **Language**: Python 3.x

## Running the Dashboard
1. Install dependencies:
   ```bash
   pip install dash plotly pandas
   ```
2. Run the notebook
3. Access dashboard at http://127.0.0.1:8050/

## Key Achievements
1. Built a responsive, real-time dashboard
2. Implemented dynamic data filtering
3. Created intuitive visualizations for business metrics
4. Enabled data-driven decision making through interactive analysis

## Data Source
Using cleaned retail dataset from Task 1, containing:
- Transaction records
- Customer information
- Product details
- Sales data
