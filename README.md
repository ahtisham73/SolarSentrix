# SolarSentrix: Solar Fault Detection, Analysis and Forecasting

## 📘 **Project Overview**
This project focuses on predicting solar power generation by analyzing data from solar power plants. Using machine learning techniques, it builds a robust pipeline for forecasting solar energy yield and detecting technical faults. The analysis leverages datasets including power generation and weather data, with models such as Linear Regression, Random Forest, and XGBoost evaluated for accuracy. The goal is to optimize energy grid management and reduce wastage by improving the reliability and efficiency of solar power predictions.

## 📂 **Datasets Used**
1. **Plant_1_Generation_Data.csv** - Solar power generation data from Plant 1.
2. **Plant_2_Generation_Data.csv** - Solar power generation data from Plant 2.
3. **Plant_1_Weather_Sensor_Data.csv** - Weather data for Plant 1.
4. **Plant_2_Weather_Sensor_Data.csv** - Weather data for Plant 2.
5. **Plant_2_Merged_Data.csv** - Merged data from both generation and weather sensors for Plant 2.

## 📝 **Main Code File**
- **Solarlytics.ipynb** - Main Jupyter notebook for data preprocessing, model training, and analysis.

## 🛠️ **Libraries Used**
- pandas
- numpy
- datetime
- scipy
- matplotlib
- seaborn
- plotly
- scikit-learn
- xgboost
- tensorflow
- scikit-learn

## 🔄 **Steps Followed**
1. **Data Preprocessing**:
   - Cleaned and integrated the datasets.
   - Performed correlation analysis to identify key relationships.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized trends in power generation over 34-day and 1-day periods.
   - Analyzed and visualized DC power trends.
3. **Technical Fault Analysis**:
   - Investigated underperforming inverters.
   - Identified non-operational periods and fault sources.
4. **Machine Learning Models**:
   - Implemented **Linear Regression**, **Random Forest Regressor**, and **XGBoost**.
   - Applied hyperparameter tuning for enhanced model performance.

## 📈 **Visualization**
The project includes various visualizations to display trends, power generation patterns, and model evaluation metrics, helping to understand solar power production dynamics.

## ⚙️ **Environment Setup**
- To set up the environment, use the following command to install the required dependencies:
    ```bash
      pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost tensorflow scipy
    ```

## 🧑‍💻 **Running the Code**

To run the code, follow these steps:

1. **Clone the repository** and navigate to the project folder.
2. **Install the required libraries** by running:
   ```bash
   pip install -r requirements.txt
