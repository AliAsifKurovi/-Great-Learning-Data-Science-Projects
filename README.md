# Great Learning Wine Classification Project

This repository contains a comprehensive machine learning project focused on classifying wine types using Random Forest, Logistic Regression, and SVM algorithms. The project involves data analysis, preprocessing, model training, evaluation, and predictions.

## Project Overview
The objective of this project is to build and evaluate multiple classification models to predict wine categories based on provided features. The dataset includes various attributes of wine samples, and the analysis identifies relationships and patterns within the data.

## Key Steps
1. **Data Understanding**:
   - Overview of the dataset.
   - Summary statistics and data types.

2. **Data Visualization**:
   - Distribution of features using histograms and boxplots.
   - Correlation analysis using a heatmap.

3. **Data Preprocessing**:
   - Handling outliers with `boxplot` and `clip()` functions.
   - Checking for and imputing missing values.

4. **Model Training**:
   - Training three models: Logistic Regression, SVM, and Random Forest.
   - Hyperparameter tuning for optimal performance.

5. **Model Evaluation**:
   - Comparison of model metrics such as accuracy, precision, recall, and F1-score.
   - Selection of the best-performing model.

6. **Prediction**:
   - Final prediction using the Random Forest model.

## Repository Structure
- `notebooks/`: Contains the Jupyter Notebook file (`wine_classification.ipynb`) with code for the entire analysis and modeling process.
- `data/`: Includes the datasets used in the project:
  - `wine_data.csv`: Original dataset.
  - `processed_data.csv`: Preprocessed dataset used for modeling.

## How to Use
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/AliAsifKurovi/Wine-Classification-Project.git
