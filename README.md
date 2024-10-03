# ML Data Cleaning and Feature Selection

## Overview
This project focuses on data preparation and feature selection to improve the performance of predictive models. It aims to assess data quality, handle missing values, understand distributions, and identify the most relevant features for effective machine learning model training. The assignment answers key questions related to data quality and predictor relevance, making it an essential guide for effective data preprocessing.

## Objectives
- Analyze data types (numeric and categorical) and detect missing values.
- Understand the distribution of numeric variables and evaluate if the ranges make sense.
- Identify useful independent variables for predicting a target using multiple methods.
- Determine the presence and quantity of missing data across training and test sets.
- Evaluate relationships and dependencies between predictor variables.
- Identify the most important predictor variables for the target.
- Compare the effect of removing and keeping outliers on model performance.
- Evaluate the effect of data removal and apply imputation techniques to recover missing values.

## Key Features
1. **Data Types Analysis**
   - Identified and differentiated between numeric and categorical data types.
2. **Missing Values**
   - Examined the dataset for missing values and quantified missing data for each feature.
3. **Variable Distribution Analysis**
   - Analyzed the distributions of numeric variables to understand their spread and any anomalies.
4. **Feature Importance Assessment**
   - Used three different methods to determine which independent variables are most predictive of the target variable.
5. **Data Integrity Check**
   - Compared training and test datasets to ensure data consistency.
6. **Outlier Handling**
   - Assessed the effect of removing outliers and keeping them on the model’s predictive accuracy.
7. **Data Imputation Techniques**
   - Randomly removed 1%, 5%, and 10% of data, and applied at least three imputation techniques to measure the accuracy of the recovered data.

## Methods Used
- **Feature Selection**: Used statistical and model-based methods to determine feature importance.
- **Outlier Analysis**: Evaluated the influence of outliers by removing them and observing changes in model performance.
- **Imputation Methods**: Tested different imputation techniques (e.g., mean, median, k-nearest neighbors) to recover removed data and analyzed residual errors.

## Prerequisites
- **Programming Language**: Python
- **Libraries Used**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, etc.
- **Environment**: Jupyter Notebook or Google Colab

## How to Run the Project
1. Open the `.ipynb` file in an IDE such as **Google Colab** or **Jupyter Notebook**.
2. Run the cells sequentially to explore the data, perform cleaning, feature selection, and analysis.

## Results
- Provided insights into which features are critical for predictive accuracy.
- Evaluated the effectiveness of different imputation techniques in handling missing data.
- Analyzed the impact of outliers and how they affect model performance.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact vishruthtv30@gmail.com .

