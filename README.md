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
- ![Pandas](https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg) [Pandas](https://pandas.pydata.org/)
- ![NumPy](https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg) [NumPy](https://numpy.org/)

### Date & Time
- ![Datetime](https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg) [datetime](https://docs.python.org/3/library/datetime.html)

### Statistics
- ![SciPy](https://raw.githubusercontent.com/devicons/devicon/master/icons/scipy/scipy-original.svg) [SciPy](https://scipy.org/)

### Visualization
- ![Matplotlib](https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg) [Matplotlib](https://matplotlib.org/)
- ![Seaborn](https://raw.githubusercontent.com/devicons/devicon/master/icons/seaborn/seaborn-original.svg) [Seaborn](https://seaborn.pydata.org/)
- ![Plotly](https://raw.githubusercontent.com/devicons/devicon/master/icons/plotly/plotly-original.svg) [Plotly](https://plotly.com/)

### Machine Learning Models
- ![Scikit-learn](https://raw.githubusercontent.com/devicons/devicon/master/icons/scikit-learn/scikit-learn-original.svg) [Scikit-learn](https://scikit-learn.org/)
- ![XGBoost](https://raw.githubusercontent.com/devicons/devicon/master/icons/xgboost/xgboost-original.svg) [XGBoost](https://xgboost.readthedocs.io/)
- ![TensorFlow](https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg) [TensorFlow](https://www.tensorflow.org/)

### Preprocessing
- ![StandardScaler](https://raw.githubusercontent.com/devicons/devicon/master/icons/scikit-learn/scikit-learn-original.svg) [StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)

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

## 💻 **Running the Code**
To run the project, clone the repository and execute the following steps:
1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost tensorflow scipy

   
