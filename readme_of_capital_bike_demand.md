# Enhancing Capital Bikeshare Demand: Analysis, Prediction and Optimization

## Table of Contents
1. [Materials and Methods](#materials-and-methods)
2. [Author](#author)
3. [Libraries Used](#libraries-used)
4. [Installation](#installation)
5. [Dataset Loading And Exploration](#dataset_loading_and_exploration)
6. [Exploratory Data Analysis (EDA)](#exploratory_data_analysis-eda)
7. [Dataset Overview](#dataset_overview)
8. [Data Cleaning And Preprocessing](#data_cleaning_and_preprocessing)
   - [Missing Values Detection And Handling](#missing_values_detection_and_handling)
9. [Analyze And Visualize Dataset Columns](#analyze_and_visualize_dataset_columns)
10. [Model Building and Training](#model_building_and_training)
11. [Clustering Analysis](#clustering_analysis)

## Project Overview
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/Pandas-1.5.3-green)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0.2-yellowgreen)](https://scikit-learn.org/stable/)
[![XGBoost](https://img.shields.io/badge/XGBoost-1.5.0-orange)](https://xgboost.readthedocs.io/en/stable/)

This project focuses on predicting the demand for Capital Bikeshare from May 2020 to August 2024. By analyzing the dataset, we aim to gain deep insights about bikes demand it helps many businesses to understand which bike types are most popular and how to optimize their offerings.

## Project Goals
1. Analyze usage frequency, daily rentals, and station details of bikes.
2. Visualize daily rentals over time according to bike type.
3. Identify and analyze the busiest stations for bike rentals.
4. Build and train machine learning models to predict demand.
5. Perform clustering analysis to explore and predict the relationships among the features.

## Outline
1. **Materials and Methods**
2. **General Part**
   - i) Libraries Import
   - ii) Data Loading and Exploration
   - iii) Data Cleaning or Preprocessing
      - Changing datatypes for improved model performance
   - iv) Exploratory Data Analysis (EDA)
      - Analyze and visualize dataset files
      - Analyze daily rentals, station list, usage frequency, and weather data
   - v) Model Training and Evaluation
3. **Clustering Analysis**

## Materials and Methods
The dataset used in this project is the Capital Bikeshare dataset covering the time period from May 2020 to August 2024, which is publicly available on [Kaggle](https://www.kaggle.com/datasets/taweilo/capital-bikeshare-dataset-202005202408). This dataset contains information about daily rental details, station lists, and weather conditions. By analyzing this dataset many businesses can determine which bike types are in high demand and make informed decisions on inventory and marketing strategies.

## Key Analysis Questions
- What is the daily rental trend over time for each bike type?
- Which station experiences the highest demand for bike rentals?
- From which stations do users predominantly start their rides, and which stations see the most drop-offs?
- How do weather conditions impact bike usage and rentals?
- What are the peak times for bike rentals throughout the day?

Additionally, we also conduct visual analyses to enhance our understanding of bike demand according to various factors.

## Libraries Used
1. **NumPy**: For numerical operations and data manipulation.
2. **Pandas**: For data analysis and manipulation.
3. **Matplotlib**: For data visualization and plotting.
4. **Seaborn**: For enhanced data visualization.
5. **Scikit-Learn**: For machine learning algorithms and model evaluation.
6. **Folium**: For creating interactive maps.
7. **GeoPandas**: For geospatial data analysis.
8. **Plotly**: For interactive data visualizations.
9. **Shapely**: For geometric operations.
10. **Linear Regression**: For predicting bike demand based on various features.
11. **Random Forest**: For robust predictions in machine learning.

## Installation
To set up the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required libraries**:
   ```bash
   pip install -r requirements.txt
   ```

   If you don't have a `requirements.txt` file, you can install the libraries individually:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn
   ```

## Conclusion
This project aims to provide valuable insights about bikes demand and predict which bike types are in the highest demand. These insights will help businesses optimize their offerings based on customer preferences and usage patterns.
## Author
* Arshman Khalid [Reach me out on LinkedIn](https://www.linkedin.com/in/arshmankhalid/).