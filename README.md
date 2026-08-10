# Iris Species Classification using Machine Learning

## Project Overview

This project focuses on classifying Iris flower species using Machine Learning.

The Iris dataset contains measurements of Iris flowers such as:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

A Random Forest Classification algorithm is used to predict the species of an Iris flower.

## Objectives

The main objectives of this project are:

- Explore the Iris dataset
- Perform Exploratory Data Analysis (EDA)
- Check missing values
- Analyze summary statistics
- Create data visualizations
- Build a Machine Learning classification model
- Evaluate the model performance
- Publish the project on Kaggle
- Upload the project to GitHub

## Dataset

This project uses the Iris dataset provided by Scikit-learn.

The dataset contains 150 samples, 4 numerical features, and 3 target classes.

### Features

1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

### Target Classes

The model classifies flowers into three Iris species:

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle
- GitHub

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the structure and characteristics of the Iris dataset.

The following steps were performed:

- Loaded the Iris dataset
- Checked dataset information
- Checked the number of rows and columns
- Checked for missing values
- Generated summary statistics
- Analyzed relationships between features
- Analyzed feature correlations

## Dataset Information

The dataset contains:

- 150 rows
- 5 columns
- 4 numerical features
- 1 target column

There are no missing values in the dataset.

## Data Visualizations

Six visualizations were created during the Exploratory Data Analysis.

### 1. Iris Species Distribution

A count plot was created to show the number of samples belonging to each Iris species.

### 2. Sepal Length Distribution

A histogram was used to visualize the distribution of sepal length values.

### 3. Sepal Width Distribution

A histogram was used to visualize the distribution of sepal width values.

### 4. Sepal Length vs Sepal Width

A scatter plot was used to analyze the relationship between sepal length and sepal width for different Iris species.

### 5. Petal Length vs Petal Width

A scatter plot was used to analyze the relationship between petal length and petal width for different Iris species.

### 6. Feature Correlation Heatmap

A correlation heatmap was created to understand the relationships between the numerical features.

## Machine Learning Model

A Random Forest Classifier was selected for this project.

Random Forest is a supervised Machine Learning algorithm that combines multiple decision trees to make predictions.

The four flower measurements were used as input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable was the Iris species.

## Train-Test Split

The dataset was divided into training and testing sets.

- Training data: 80%
- Testing data: 20%

The training dataset contains 120 samples, while the testing dataset contains 30 samples.

## Model Training

The Random Forest Classifier was trained using the training dataset.

The model was then used to predict the Iris species of the testing dataset.

## Model Evaluation

The model was evaluated using the following metrics:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Accuracy Score

The Random Forest model achieved an accuracy of:

**90%**

This means that the model correctly classified 90% of the samples in the test dataset.

### Confusion Matrix

The confusion matrix was used to compare the actual Iris species with the predicted species.

It helps identify the number of correct and incorrect predictions for each class.

### Classification Report

The classification report provides the following evaluation metrics:

- Precision
- Recall
- F1-Score
- Support

The model performed well across the three Iris species.

## Results

The Random Forest Classifier achieved:

**Accuracy: 90%**

The model successfully classified the Iris flower species based on their measurements.

## Project Structure

Iris-Species-Classification/
│
├── Iris_Classification.ipynb
├── README.md
└── requirements.txt

## Requirements

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

These dependencies are listed in the requirements.txt file.

## How to Run the Project

### 1. Clone the Repository

Clone this repository to your local computer.

```bash
git clone https://github.com/jagadishbhumika453-blip/Iris-Species-Classification.git
