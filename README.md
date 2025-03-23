Advertising Data Analysis and Prediction

This project is part of my Intellipaat Data Science course. It involves analyzing an advertising dataset to optimize marketing spend using data preprocessing, exploratory data analysis (EDA), statistical analysis, and machine learning.

## Project Overview
- **Objective**: Optimize marketing spend by analyzing advertising performance and predicting post-click sales.
- **Dataset**: `advertising_data.csv` contains data on campaigns, user engagement, banners, placements, and performance metrics.
- **Tasks**:
  1. Preprocess the data (handle missing values, feature engineering).
  2. Perform EDA to identify patterns (e.g., campaign performance, user engagement impact).
  3. Conduct statistical analysis (descriptive stats, T-test for conversion rates).
  4. Build a Random Forest model to predict post-click sales and devise a strategy.

## Files
- `Intellipaat_Assignment1.ipynb`: Jupyter Notebook with the complete code and analysis.
- `advertising_data.csv`: Original dataset.
- `preprocessed_advertising_data.csv`: Preprocessed dataset.
- `heatmap.png`, `cost_vs_revenue.png`, etc.: Visualizations from EDA.

## Key Insights
- Campaign 0 (camp 1) has the highest revenue-to-cost ratio.
- High user engagement significantly increases conversion rates (p < 0.05).
- Banner size 4 yields the highest click-through rate (CTR).
- The Random Forest model identifies `cost`, `revenue`, and `clicks` as key predictors of sales.

## How to Run
1. Open `Intellipaat_Assignment1.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure the datasets (`advertising_data.csv`, `preprocessed_advertising_data.csv`) are in the same directory.
3. Run the notebook to reproduce the analysis.

## Visualizations
- **Correlation Heatmap**:
  ![Correlation Heatmap](heatmap.png)
- **Cost vs Revenue by Campaign**:
  ![Cost vs Revenue](cost_vs_revenue.png)
- **User Engagement vs Conversions**:
  ![User Engagement vs Conversions](user_engagement_conversions.png)
- **Average CTR by Banner Size**:
  ![CTR by Banner](ctr_by_banner.png)

## Tools Used
- Python (pandas, numpy, sklearn, matplotlib, seaborn)
- Google Colab
