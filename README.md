# Project_Data_Mining

# Student Performance Analysis and Prediction

## Overview
This project analyzes student performance data using data science and machine learning techniques.  
The goal is to understand the factors that influence academic performance and build models that can predict student outcomes.

The project follows a complete data science workflow including data cleaning, exploratory data analysis, machine learning modeling, and clustering.

---

## Dataset
The dataset contains various attributes related to students such as:

- Demographic information
- Family background
- Study habits
- Internet usage
- Previous academic performance

The final grade of students is used as the main variable for analysis and prediction.

---

## Project Steps

### 1. Data Exploration
Exploratory Data Analysis (EDA) was performed to understand the structure of the dataset and identify relationships between variables.

### 2. Data Cleaning and Preprocessing
Several preprocessing steps were applied:

- Handling missing values using `SimpleImputer`
- Converting categorical variables to numerical values
- Applying One-Hot Encoding
- Converting binary values (yes/no) to numerical format

### 3. Feature Engineering
The final student grade (G3) was transformed into performance categories such as:

- Poor
- Good
- Excellent

This transformation allows classification models to predict student performance levels.

### 4. Machine Learning Models
Different machine learning algorithms were applied including:

- Random Forest Classifier
- Linear Regression
- Random Forest Regressor

The models were evaluated using metrics such as:

- Accuracy
- F1-score
- R² score
- Mean Squared Error

### 5. Clustering Analysis
K-Means clustering was used to group students with similar characteristics and discover hidden patterns in the data.

### 6. Data Visualization
Visualization techniques were used to better understand patterns and relationships using:

- Matplotlib
- Seaborn

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Goal
The main objective of this project is to:

- Analyze factors affecting student academic performance
- Build predictive models for student outcomes
- Discover patterns among students using clustering
- Demonstrate a complete data science workflow

---

## Author
Data Science Student
