# Solarlytics: Solar Power Generation Forecasting

## 📘 **Project Overview**
Solarlytics is a data science project designed to predict solar power generation using machine learning models. The project analyzes solar generation and weather data from multiple plants to optimize energy yield prediction, enabling better grid management and energy distribution.

## 📂 **Datasets Used**
1. **Plant_1_Generation_Data.csv** - Solar power generation data from Plant 1.
2. **Plant_2_Generation_Data.csv** - Solar power generation data from Plant 2.
3. **Plant_1_Weather_Sensor_Data.csv** - Weather data for Plant 1.
4. **Plant_2_Weather_Sensor_Data.csv** - Weather data for Plant 2.
5. **Plant_2_Merged_Data.csv** - Merged data from both generation and weather sensors for Plant 2.

## 📝 **Main Code File**
- **Solarlytics.ipynb** - Main Jupyter notebook for data preprocessing, model training, and analysis.

## 🛠️ **Libraries Used**
### Data Manipulation
- <p align="left">
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="25" height="25"/> </a>
  <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="25" height="25"/> </a>
</p>

### Date & Time
- <p align="left">
  <a href="https://docs.python.org/3/library/datetime.html" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="datetime" width="25" height="25"/> </a>
</p>

### Statistics
- <p align="left">
  <a href="https://scipy.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scipy/scipy-original.svg" alt="scipy" width="25" height="25"/> </a>
</p>

### Visualization
- <p align="left">
  <a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" width="25" height="25"/> </a>
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/seaborn/seaborn-original.svg" alt="seaborn" width="25" height="25"/> </a>
  <a href="https://plotly.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/plotly/plotly-original.svg" alt="plotly" width="25" height="25"/> </a>
</p>

### Machine Learning Models
- <p align="left">
  <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikit-learn/scikit-learn-original.svg" alt="scikit-learn" width="25" height="25"/> </a>
  <a href="https://xgboost.readthedocs.io/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/xgboost/xgboost-original.svg" alt="xgboost" width="25" height="25"/> </a>
  <a href="https://www.tensorflow.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="tensorflow" width="25" height="25"/> </a>
</p>

### Preprocessing
- <p align="left">
  <a href="https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikit-learn/scikit-learn-original.svg" alt="scikit-learn" width="25" height="25"/> </a>
</p>

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
To set up the environment, use the following command to install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost tensorflow scipy
