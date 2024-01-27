# Multiclass classification Car Evaluation Predictive Analysis

## Overview
This repository hosts the code and findings from a predictive analysis conducted on a car evaluation dataset, available at [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Car+Evaluation). 
The analysis leverages various classification techniques, including Decision Trees, k-Nearest Neighbors (k-NN), Logistic Regression, Naive Bayes (NB), and Support Vector Machines (SVM), to predict car evaluations based on their characteristics.

## Predictive Modeling Process
The project follows these steps:
1. **Data Acquisition**: Downloading the car evaluation dataset from the UCI repository.
2. **Data Preprocessing**: Converting ordinal attributes to numerical or categorical formats and discussing the pros and cons of each approach.
3. **Model Training and Tuning**: Applying classification techniques with different parameter values to find the optimal model configurations.
4. **Evaluation**: Assessing models based on overall accuracy, per-class performance, confusion matrix, precision, recall, and F1-scores.

## Results and Discussion
- The best-performing model achieved an overall predictive accuracy of 99.62%.
- Per-class performance analysis revealed high precision, recall, and F1-scores across all classes, with a minor precision drop for the 'good' class.
- The analysis includes a discussion on the treatment of ordinal variables, with a conclusion that numerical conversion yielded better predictive performance.

## Converting Ordinal Data
The decision to treat ordinal variables as numeric or categorical is explored, with findings indicating that numerical conversion led to improved model accuracy. This section discusses the implications of each approach and the rationale behind the chosen method.

## Final Model and Performance
The repository details the best predictive model, including its configuration, overall accuracy, and per-class performance metrics. The robustness of the model across classes with varying representation levels is also discussed.

## Usage
Instructions for setting up the environment, running the analysis, and interpreting the results are provided, enabling users to replicate the study or apply the methodology to similar datasets.

## Contribution
Contributions to enhance the analysis, improve model performance, or extend the documentation are welcome. Feel free to fork the repository and submit pull requests.

## License
This project is released under the MIT License.
