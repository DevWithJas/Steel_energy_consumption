<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Steel Energy Consumption Project README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        h1, h2, h3 {
            text-align: center;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .feature-list, .steps-list, .key-files-list, .requirements-list, .future-work-list {
            list-style-type: none;
            padding: 0;
        }
        .feature-list li, .steps-list li, .key-files-list li, .requirements-list li, .future-work-list li {
            background: #e2e2e2;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .feature-list li:hover, .steps-list li:hover, .key-files-list li:hover, .requirements-list li:hover, .future-work-list li:hover {
            background: #d0d0d0;
        }
        .image-container {
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Steel Energy Consumption Data Analysis and Predictive Maintenance Project</h1>
        
        <h2>Overview</h2>
        <p>This project focuses on analyzing steel energy consumption data from the <code>STEEL_ENERGY</code> database to identify patterns and optimize energy usage. The analysis involves extracting, analyzing, and visualizing data using Python and MySQL, emphasizing predictive maintenance.</p>
        
        <h2>Features</h2>
        <ul class="feature-list">
            <li><strong>Database Connection:</strong> Utilize Python libraries to connect to and query the MySQL database.</li>
            <li><strong>Data Exploration:</strong> Identify data types, check for missing or duplicate values, and perform descriptive statistics.</li>
            <li><strong>Visualization:</strong> Employ Python's Matplotlib and Seaborn libraries to create histograms, box plots, and time-series plots to visualize data distributions and trends.</li>
            <li><strong>Anomaly Detection:</strong> Implement various statistical techniques to detect outliers and anomalies in energy consumption, which are critical for predictive maintenance.</li>
            <li><strong>Correlation Analysis:</strong> Explore relationships between multiple variables using a correlation matrix to guide feature selection for modeling.</li>
            <li><strong>Predictive Modeling:</strong> Use machine learning models to predict anomalies and identify opportunities for optimizing energy management.</li>
        </ul>

        <div class="image-container">
            <img src="https://github.com/user-attachments/assets/d3bb2732-457b-4c12-869a-fcc555d328ea" alt="Data Visualization">
            <img src="https://github.com/user-attachments/assets/6f720556-0c4d-4917-970a-0b14e66fe731" alt="Data Visualization">
            <img src="https://github.com/user-attachments/assets/58a062d7-5c26-408e-8f4e-be6e5e974cb1" alt="Data Visualization">
        </div>

        <h2>How to Run</h2>
        <ol class="steps-list">
            <li><strong>Setup Environment:</strong> Ensure Python 3.x is installed. Install required packages: <code>mysql.connector</code>, <code>pandas</code>, <code>matplotlib</code>, <code>seaborn</code>, <code>scikit-learn</code>.</li>
            <li><strong>Database Configuration:</strong> Set up the <code>STEEL_ENERGY</code> database in MySQL. Update database connection settings in the script.</li>
            <li><strong>Execute Analysis:</strong> Run the Python script to perform data extraction, cleaning, exploration, and visualization. Analyze the output plots and statistical summaries.</li>
        </ol>

        <h2>Key Files</h2>
        <ul class="key-files-list">
            <li><code>Steel_energy_consumption.ipynb</code>: Jupyter notebook containing all scripts and analysis.</li>
            <li><code>data_visualization.py</code>: Python script for generating visualizations.</li>
            <li><code>anomaly_detection.py</code>: Scripts for implementing and evaluating anomaly detection techniques.</li>
        </ul>

        <h2>Requirements</h2>
        <ul class="requirements-list">
            <li>Python 3.x</li>
            <li>MySQL</li>
            <li>Libraries: <code>mysql.connector</code>, <code>pandas</code>, <code>matplotlib</code>, <code>seaborn</code>, <code>scikit-learn</code></li>
        </ul>

        <h2>Future Work</h2>
        <ul class="future-work-list">
            <li>Enhance the predictive models by incorporating more sophisticated machine learning algorithms.</li>
            <li>Automate the data updating and analysis process to run this analysis periodically.</li>
            <li>Explore the impact of other variables on energy consumption through deeper multivariate analysis.</li>
        </ul>

        <div class="image-container">
            <img src="https://github.com/user-attachments/assets/9a2f6191-67e3-4522-9323-b2c6e7eae147" alt="Power BI Image">
        </div>

        <p>This project is a comprehensive attempt to understand and optimize energy usage in steel production, crucial for cost reduction and environmental sustainability.</p>
    </div>

</body>
</html>

