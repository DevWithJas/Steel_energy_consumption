# Predictive Maintenance and Anomaly Detection in Energy Efficiency

## Overview
This project aims to enhance the energy efficiency of a system by detecting and predicting anomalies in `Lagging_Current_Reactive.Power_kVarh` and `Lagging_Current_Power_Factor` using a combination of data analysis and machine learning techniques.

## Goals
1. **Data Analysis**: Perform exploratory data analysis (EDA) to identify patterns and anomalies.
2. **Anomaly Detection**: Use machine learning models to predict and detect anomalies.
3. **Efficiency Improvement**: Quantify the potential improvements in energy efficiency by removing anomalies.

## Data Analysis

### Steps Taken
1. **Data Loading and Preparation**:
    - Loaded the dataset and ensured proper data types.
    - Calculated Z-scores for `Lagging_Current_Reactive.Power_kVarh` and `Lagging_Current_Power_Factor`.

2. **Rolling Statistics**:
    - Calculated rolling mean and standard deviation for both `Lagging_Current_Reactive.Power_kVarh` and `Lagging_Current_Power_Factor`.

3. **Anomaly Detection Techniques**:
    - **Z-score Analysis**: Marked anomalies where Z-scores exceeded ±3.
    - **Rolling Statistics**: Identified anomalies outside the rolling mean ±2 standard deviations.
    - **Local Outlier Factor (LOF)**: Detected local anomalies.
    - **One-Class SVM**: Identified anomalies using a support vector machine.

4. **Visualization**:
    - Plotted time series and scatter plots to visualize anomalies.
    - Used KDE plots to show data density and anomalies.

### Results
- **18% Potential Efficiency Improvement**: Initial analysis indicated that removing anomalies could improve efficiency by up to 18%.

## Machine Learning

### Model Selection
- **LSTM Model**: Chosen for its effectiveness in handling time series data.
- **Hybrid Approach**: Combined LSTM with Isolation Forest for robust anomaly detection.

### Model Performance
- **Precision**: 90.64%
- **Recall**: 78.67%
- **F1-score**: 84.24%
- **Accuracy**: 93.53%

### Steps Taken
1. **Data Preprocessing**:
    - Scaled the data using `MinMaxScaler`.
    - Created sequences for the LSTM model.

2. **Model Training**:
    - Built and trained the LSTM model.
    - Evaluated the model using precision, recall, F1-score, and accuracy.

3. **Anomaly Prediction**:
    - Used the trained model to predict anomalies.
    - Calculated reconstruction error and set a threshold for anomaly detection.

4. **Results**:
    - **Confusion Matrix**: Demonstrated the model's performance in detecting anomalies.
    - **Efficiency Improvement**: Removing predicted anomalies resulted in a 1.22% efficiency improvement.

## Conclusion
The LSTM model effectively predicts anomalies, supporting proactive maintenance. High precision and accuracy enhance operational efficiency, reduce energy usage, and lead to significant cost savings. Initial data analysis indicated a potential 18% improvement in energy efficiency by removing anomalies, serving as a target for future model improvements.

## Next Steps
1. **Model Refinement**: Further improve the anomaly detection model to achieve closer to the 18% efficiency improvement target.
2. **Integration**: Implement the model into a real-time system for continuous monitoring and maintenance.
3. **Visualization**: Create interactive dashboards using Power BI or Tableau for better insights and decision-making.

## Files in This Repository
- **data/**: Directory containing the dataset.
- **notebooks/**: Jupyter notebooks for data analysis and model training.
- **scripts/**: Python scripts for data preprocessing, model training, and evaluation.
- **README.md**: This file, providing an overview of the project.

## Dependencies
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- keras
- tensorflow

## Usage
1. **Data Analysis**:
    - Run the notebooks in the `notebooks` directory for exploratory data analysis.
2. **Model Training**:
    - Use the scripts in the `scripts` directory to train and evaluate the anomaly detection model.
3. **Visualization**:
    - Use Power BI or Tableau to create interactive dashboards based on the analysis and model predictions.


![image](https://github.com/user-attachments/assets/132460b0-973a-4026-a56f-d7da3c540366)

