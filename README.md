# EEG Data Processing and Classification

This repository contains the code and information for an EEG data analysis project, which was my Senior Project in University. 
The project is accompanied by Jupyter Notebooks, which explore methods for analyzing EEG data and classifying it into different categories. 
The data used for this project is obtained from an open-source EEG database and is related to a visual 
task conducted by a group of alcoholics and a control group.

To see the project details, we highly recommend you to check out Jupyter Notebooks, which are available in English and Georgian languages:
1. [Notebook in English](./notebook-en.ipynb)
2. [Notebook in Georgian](./notebook-ge.ipynb)

## Contents


Notebooks consist of several sections, where code in each section demonstrates 
each of the concepts in detail. It begins with an introduction, followed by data explanation, extraction, visualization, and transformation 
sections. After that, the notebook moves on to classification, which includes the following sub-sections: 
Logistic Regression, Support Vector Machines (with and without PCA), K-Nearest Neighbors and Naive Bayes. 

The repository includes table obtained from the classification results of the EEG data. 
The performance of each method was evaluated using accuracy, precision, recall and area under the curve (AUC). Here are the results 
obtained from the classification methods:

| Method                    | Accuracy | Precision | Recall  | AUC   |
|---------------------------|----------|-----------|---------|-------|
| Logistic Regression       | 86.5%    | 88.4%     | 91.1%   | 92.7% |
| Support Vector Machines   | 86.4%    | 88.8%     | 90.5%   | -     |
| SVM + PCA                 | 75.8%    | 77.8%     | 87.6%   | -     |
| K-Nearest Neighbors       | 44%      | -         | -       | -     |
| Naive Bayes               | 68.6%    | 76.9%     | 73.5%   | 74.5% |
