# Fairness of Predictive Modelling Based on Traffic Check Data

## Overview
This project aims to develop a predictive model for arrest decisions using the North Carolina Policing Dataset. The focus is on evaluating the fairness of the model, particularly in terms of gender, age, and race, and adjusting the model to maintain high accuracy while ensuring fairness.

## Data Preprocessing
The dataset underwent significant preprocessing, including handling missing values, dropping irrelevant features, and normalizing certain data points. Features like 'drugs related stop', 'district', and 'state' were evaluated for their relevance and impact on the model.

## Model Selection and Fine-Tuning
Several binary classifiers, including Logistic Regression and K-Nearest Neighbours (KNN), were compared. A fine-tuned KNN model, achieving an optimal accuracy of 0.95, was selected as the final model.

## Fairness Evaluation
Fairness was assessed using measures like independence, separation, and sufficiency. The model's fairness was evaluated by examining the correlation between arrest decisions and sensitive features such as gender, age, and race.

## Conclusion
The project demonstrates the intricate balance between accuracy and fairness in predictive modeling. While the model showed high accuracy, its fairness needed careful adjustments to ensure unbiased decision-making.

## Authors
- Taeyoung Kim (ty.kim@tum.de)
- Mingi Kang (mingi.kang@tum.de)
