# Traffic Prediction Using Machine Learning Techniques

## Overview
A comprehensive machine learning project that forecasts traffic volume at different junctions using temporal features and advanced ML algorithms.

## Features
- **Data Processing**: Date-time feature engineering, normalization, and correlation analysis
- **Visualization**: Time-series analysis, hourly/daily/monthly patterns, rolling averages
- **Models**: Linear Regression (baseline) and Multi-Layer Perceptron Neural Network
- **Interactive Prediction**: Real-time traffic volume prediction with shortest path calculation

## Dataset
Traffic volume data from Kaggle including:
- Date and time information
- Junction-specific vehicle counts
- Temporal patterns and trends

## Model Performance
- **Linear Regression**: Baseline model with MSE evaluation
- **MLP Neural Network**: Advanced model with dropout regularization and early stopping
- **Evaluation Metric**: Mean Absolute Error (MAE)

## Key Components
1. **Feature Engineering**: Year, month, day, hour, day-of-week extraction
2. **Time-Series Analysis**: Rolling averages and difference analysis
3. **Data Preprocessing**: Z-score normalization and 70/30 train-test split
4. **Model Training**: Early stopping to prevent overfitting
5. **Interactive Playground**: Real-time prediction interface

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow/Keras
- Google Colab

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Install required dependencies
3. Run all cells sequentially
4. Use the interactive playground at the end for custom predictions

## Results
The MLP model successfully captures non-linear traffic patterns, providing improved accuracy over the baseline Linear Regression model for urban traffic management applications.

## Files
- `traffic_prediction_ml.ipynb` - Main notebook with complete implementation
- `REPORT.pdf` - Detailed project report
- `presentation.pptx` - Project presentation (if included)

## Author
Mayank Kumar - IIT Jodhpur
