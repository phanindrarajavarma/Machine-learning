# Online News Popularity Project Report
This repository contains the project report for Group 6 in the IE7300 Statistical Learning for Engineers course, Spring 2023, under the guidance of Professor Ramin Mohammadi.

Abstract
This report delves into the use of machine learning models for predicting the popularity of online news articles. The study focuses on various techniques, including linear regression for predicting the number of shares an article might receive, and classification models such as logistic regression, support vector machines, and neural networks to assess the popularity of articles.

Introduction
In a digital age where online platforms replace traditional media, understanding the potential popularity of articles is vital for news outlets. Marketing decisions often depend on predicting an article's success. This study aims to analyze the factors contributing to an article's popularity and create models to forecast its performance. The findings promise more informed marketing strategies for news outlets.

Data Source and Problem Definition
The dataset obtained from the UCI Machine Learning Repository covers statistics of articles published by Mashable. The study primarily focuses on estimating an article's popularity based on the number of shares. The project assumes no direct relationship between the article's quality and its popularity or the reader's preference.

Data Description and Cleaning
The dataset encompasses 61 attributes, including predictors, non-predictive variables like URL and time, and the target variable—shares. Through exploratory data analysis, correlations, and distribution checks, relevant features are identified for modeling. The dataset is relatively clean, minimizing the need for extensive data cleaning or imputation.

Model Description
The project involves multiple regression and classification models like Linear Regression, Logistic Regression, Support Vector Machines, and Neural Networks. The models' evaluation is based on metrics like RMSE and MAE for regression, and accuracy for classification. To ensure model generalization, datasets are split and validated.

Model Implementation and Evaluation
Each model's implementation and evaluation is explained in the report. The Linear Regression models used Ridge and Lasso regularization, while logistic regression and SVM techniques are detailed. The report discusses the neural network architectures and their performance based on accuracy.

Discussion and Conclusion
The report presents the optimal models based on the criteria for regression and classification tasks. Additionally, it highlights the top 10 attributes that significantly influence an article's share count, as identified by the linear regression model.

Profiling
The influential attributes on the target variable 'Shares' are detailed here, providing insights into the features that strongly impact an article's popularity.

GitHub Repository
The full report, along with the project code, can be found in the GitHub repository. The code and comprehensive documentation aim to aid in understanding the study's methodology and findings.
