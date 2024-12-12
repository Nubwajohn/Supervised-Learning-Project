# Supervised-Learning-Project
Supervised Learning Foundations Project: ReCell

## About

The rising potential of this comparatively under-the-radar market fuels the need for an ML-based solution to develop a dynamic pricing strategy for used and refurbished devices. ReCell, a startup aiming to tap the potential in this market.

*Disclaimer: All datasets and reports do not represent any company, institution, or country, but just a dummy dataset for learning purposes.*

## Project Overview

Predicting Prices of Used Phones and Tablets: Analyze the used device dataset, build a model that helps develop a dynamic pricing strategy for used and refurbished devices, and identify factors that significantly influence the price.

## Data Sources

The primary dataset utilized for this analysis is the “used_device_data.csv” file, which contains a range of attributes related to used and refurbished phones and tablets. The data was collected in 2021, providing valuable insights into various factors that influence device pricing and demand during that period. The detailed data dictionary is given below.

**Data Dictionary**

- brand_name: Name of manufacturing brand
- os: OS on which the device runs
- screen_size: Size of the screen in cm
- 4g: Whether 4G is available or not
- 5g: Whether 5G is available or not
- main_camera_mp: Resolution of the rear camera in megapixels
- selfie_camera_mp: Resolution of the front camera in megapixels
- int_memory: Amount of internal memory (ROM) in GB
- ram: Amount of RAM in GB
- battery: Energy capacity of the device battery in mAh
- weight: Weight of the device in grams
- release_year: Year when the device model was released
- days_used: Number of days the used/refurbished device has been used
- normalized_new_price: Normalized price of a new device of the same model in euros
- normalized_used_price: Normalized price of the used/refurbished device in euros

  
## Tools

- Programming Language: Python.
- Data Manipulation & Analysis Libraries: Pandas, NumPy.
- Data Visualization Libraries: Matplotlib, Seaborn.
- Machine Learning Library: Scikit-Learn, sklearn.model_selection.
- linear regression_model: sklearn.linear_model, statsmodels.api
- Model performance: sklearn.metrics
- Compute VIF: statsmodels.stats.outliers_influence
- Data Preprocessing & Exploratory Data Analysis (EDA) Tools:Excel, Google Colab.

