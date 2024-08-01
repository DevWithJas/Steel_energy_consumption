### README for Steel Energy Consumption Data Analysis and Predictive Maintenance Project

#### Overview
This project focuses on analyzing steel energy consumption data from the `STEEL_ENERGY` database to identify patterns and optimize energy usage. The analysis involves extracting, analyzing, and visualizing data using Python and MySQL, emphasizing predictive maintenance.

#### Features
1. **Database Connection**: Utilize Python libraries to connect to and query the MySQL database.
2. **Data Exploration**: Identify data types, check for missing or duplicate values, and perform descriptive statistics.
3. **Visualization**: Employ Python's Matplotlib and Seaborn libraries to create histograms, box plots, and time-series plots to visualize data distributions and trends.
4. **Anomaly Detection**: Implement various statistical techniques to detect outliers and anomalies in energy consumption, which are critical for predictive maintenance.
5. **Correlation Analysis**: Explore relationships between multiple variables using a correlation matrix to guide feature selection for modeling.
6. **Predictive Modeling**: Use machine learning models to predict anomalies and identify opportunities for optimizing energy management.

#### How to Run
1. **Setup Environment**:
   - Ensure Python 3.x is installed.
   - Install required packages: `mysql.connector`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.
2. **Database Configuration**:
   - Set up the `STEEL_ENERGY` database in MySQL.
   - Update database connection settings in the script.
3. **Execute Analysis**:
   - Run the Python script to perform data extraction, cleaning, exploration, and visualization.
   - Analyze the output plots and statistical summaries.

#### Key Files
- **Steel_energy_consumption.ipynb**: Jupyter notebook containing all scripts and analysis.
- **data_visualization.py**: Python script for generating visualizations.
- **anomaly_detection.py**: Scripts for implementing and evaluating anomaly detection techniques.

#### Requirements
- Python 3.x
- MySQL
- Libraries: `mysql.connector`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

#### Future Work
- Enhance the predictive models by incorporating more sophisticated machine learning algorithms.
- Automate the data updating and analysis process to run this analysis periodically.
- Explore the impact of other variables on energy consumption through deeper multivariate analysis.

This project is a comprehensive attempt to understand and optimize energy usage in steel production, crucial for cost reduction and environmental sustainability.



Power BI Images : 

![Screenshot 2024-08-01 153815](https://github.com/user-attachments/assets/9a2f6191-67e3-4522-9323-b2c6e7eae147)
