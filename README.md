# Multi_Class_URL_Classification
This project focuses on training a multi-class URL classification model using a dataset labeled with categories such as Benign, Defacement, Phishing, and Malware. The dataset is preprocessed and divided into training and testing sets to ensure reliable model evaluation.

**The project involves the following steps:**

***Data Preparation:*** The dataset is prepared by preprocessing and splitting it into training and testing sets. Feature engineering techniques are applied to extract relevant features from the URLs, such as 'use_of_ip', 'count@', 'sus_url' etc.

***Model Training:*** Several popular machine learning models, including MLP, Random Forest, Naive Bayes, AdaBoost, K-Nearest Neighbors, and Extra Trees, are trained using the training set. These models learn to classify URLs into their respective categories based on the extracted features.

***Model Evaluation***: The trained models are evaluated using the testing set. Performance metrics such as accuracy, precision, recall, and F1-score are calculated for each model to assess their classification performance. Additionally, a confusion matrix is generated to visualize the models' performance in differentiating between the URL categories.

***Results Analysis:*** The evaluation results, including accuracy, precision, recall, and F1-score, are collected and presented in a models report table. This table provides a comprehensive comparison of the performance metrics for each model, enabling informed decision-making for selecting the most effective model for URL classification.

***Visualization and GUI:*** The evaluation results are further visualized using bar charts. These charts provide an intuitive visual representation of the performance metrics for each model, facilitating easy comparison and analysis. Additionally, the IPython.display library is utilized to create an attractive graphical user interface (GUI) that enhances the user experience by providing an interactive interface to interact with the project and view the evaluation results.

********************************************************************************************************************************************************************
# Machine Learning Model Evaluation

This repository contains code for evaluating machine learning models on a dataset. The code performs model evaluation using various metrics such as accuracy, precision, recall, and F1-score. The evaluation results are visualized using Plotly.

## Prerequisites

Before running the code, ensure that you have the following dependencies installed:

- Python (version 3.6 or higher)
- Pandas
- Scikit-learn
- Plotly

## Getting Started

1. Clone the repository:


2. Navigate to the project directory:


3. Install the required dependencies:


4. Replace the placeholders with your own data:

- Replace `models` dictionary with your own machine learning models.
- Replace `X_test` and `y_test` with your own test data.

5. Run the script:


This will evaluate the models, generate evaluation reports, and display visualizations.

## Results

The evaluation results are displayed as a table and bar charts using Plotly. The table includes metrics such as accuracy, precision, recall, and F1-score for each model. The bar charts visualize the performance of each model across different metrics.

## Dataset
- The dataset used for evaluation is from https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset.

Happy coding!



