# Predicting Banking Customer Attrition with Neural Networks and EDA Approach

## Overview

This project aims to predict customer attrition in a banking dataset using machine learning techniques, specifically Neural Networks (NN), Logistic Regression, and Random Forest Classifier. Exploratory Data Analysis (EDA) is performed to gain insights into the dataset, followed by the implementation of predictive models.

## Requirements

- Python 3.x
- Libraries: scikit-learn, keras, seaborn, matplotlib, pandas

## Implementation

### 1. Exploratory Data Analysis (EDA)

- **Dataset**: The analysis begins with understanding the dataset, including features such as Credit Score, Age, Estimated Salary, and others.
  
- **Correlation Analysis**: Visualizations are created to explore correlations between numerical variables, providing insights into potential factors affecting customer attrition.

- **Data Preprocessing**: Techniques like Ordinal Encoding are applied to transform categorical variables into ordinal integers, facilitating better understanding by machine learning algorithms.

### 2. Modeling

#### 2.1 Logistic Regression

- **Training**: Logistic Regression is employed for binary classification, trained on the dataset to predict customer attrition.

- **Evaluation**: Metrics such as confusion matrix, classification report, accuracy, and ROC AUC scores are used to evaluate the model's performance on both training and test datasets.

#### 2.2 Random Forest Classifier

- **Training**: A Random Forest Classifier is trained to predict customer attrition, offering an ensemble approach for improved accuracy.

- **Evaluation**: Similar evaluation metrics are employed to assess the model's performance on both training and test datasets.

#### 2.3 Neural Networks (NN)

- **Architecture**: A Neural Network is designed and trained to predict customer attrition, with appropriate layers and activation functions.

- **Evaluation**: The model's accuracy and ROC AUC scores are computed and compared to other models.

### 3. Results and Visualization

- Results of each model, including accuracy and ROC AUC scores, are presented in tabular form.

- Visualizations, such as bar charts, illustrate the comparative performance of different models.

## How to Use

1. Install the required libraries: 
2. Run the provided Jupyter Notebook or Python script to execute the entire project.
3. Explore the EDA findings, model results, and visualizations in the output.

Feel free to customize the code and adapt it to your specific dataset or project requirements.
