### Analysis of Lung Cancer Factors to Predict Risk
This project aims to develop predictive models for assessing lung cancer risk based on a variety of clinical, demographic, and environmental factors. By analyzing these risk factors, we strive to facilitate early detection, support preventative measures, and enhance understanding of lung cancer progression.

## Table of Contents
Overview
Dataset
Project Goals
Methodology
Data Processing
Data Analysis and Visualization
Predictive Modeling
Results
Limitations
Setup and Installation
Future Work
Acknowledgments

## Overview
Lung cancer remains a leading cause of cancer-related deaths, highlighting the need for robust predictive tools to identify individuals at risk. This project evaluates factors such as smoking, air pollution, occupational hazards, and genetic predisposition to estimate lung cancer severity. Models constructed include linear regression, decision tree classifier, and k-nearest neighbors, each offering insights into risk levels.

## Dataset
The dataset used in this project is sourced from Data.World, containing clinical and lifestyle information on 1,000 lung cancer patients. Key factors include smoking habits, occupational exposure, and various comorbidities.

## Data Attributes
The dataset comprises:
Demographics: Age, Gender
Health Behaviors: Smoking, Alcohol Consumption, Diet
Environmental Risks: Air Pollution, Occupational Hazards, Passive Smoking
Symptoms: Coughing, Chest Pain, Weight Loss, etc.

## Project Goals
Identify Key Risk Factors: Determine which factors are most strongly correlated with lung cancer severity.
Analyze Interactions: Explore interactions between risk factors that may amplify cancer risk.
Predictive Modeling: Construct models to predict lung cancer severity.

## Methodology
Data Collection: Data obtained from an open-source platform with a focus on factors associated with lung cancer.
Data Cleaning: Handled missing values, dropped irrelevant data, standardized severity levels.
Feature Engineering: Grouped factors based on relevance to lung cancer as confirmed by scientific literature.
Model Construction: Linear regression for continuous risk scores, decision tree and k-nearest neighbors for categorical predictions.

## Data Processing
Data Cleaning: Removed patient IDs, handled missing/duplicate values, and standardized categorical labels.
Normalization: Standardized the scales of variables for consistent comparison across features.

## Data Analysis and Visualization
Key analyses included:
Shapiro-Wilk Test: Assessed normality of data distribution.
Correlation Analysis: Measured factor correlations with lung cancer severity.
Heatmaps and Scatter Plots: Visualized inter-factor relationships and severity trends.
Histograms and Pie Charts: Displayed age distribution, factor prevalence, and severity levels.

## Predictive Modeling
Three models were tested:
Linear Regression: Predicts continuous lung cancer risk levels, providing a score from 1 to 9.
Decision Tree Classifier: Classifies patients into severity levels based on hierarchical factor importance.
K-Nearest Neighbors (KNN): Predicts severity level based on similarities with other patients.

## Model Performance
Accuracy: Decision tree and KNN models showed high accuracy; linear regression provided detailed risk scores.
Interpretability: Decision trees offered insight into key risk factors for each severity level.
Generalizability: High accuracy was achieved, though overfitting remains a potential concern due to limited data scope.

## Results
Top Correlated Factors: Obesity, coughing of blood, dust allergy, passive smoking, and air pollution showed strong correlations with lung cancer severity.
Inter-factor Correlations: High correlations among factors like smoking, pollution, and occupational hazards suggest combined influence on severity.
Model Insights: The decision tree and KNN models offer high accuracy for categorical severity prediction, while linear regression provides more granularity.

## Limitations
Sample Exclusivity: The dataset contains only lung cancer patients, limiting model generalizability.
Factor Subjectivity: Some factors, like severity classification, depend on clinical judgment and may introduce variability.
Potential Overfitting: High accuracy may suggest overfitting; thus, additional testing on a separate validation cohort is recommended.

## Acknowledgments
We extend our thanks to Data.World for providing the dataset and to the American Cancer Society for risk factor insights.
