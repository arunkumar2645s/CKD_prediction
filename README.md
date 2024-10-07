# Chronic Kidney Disease (CKD) Risk Prediction Using Machine Learning

## Overview

Chronic Kidney Disease (CKD) is a global health issue, affecting millions worldwide and often progressing without symptoms until reaching advanced stages. Early detection is critical for improving patient outcomes and reducing healthcare costs associated with treatments like dialysis and kidney transplantation. This project aims to enhance CKD risk prediction by applying various machine learning (ML) techniques to patient data.

## Key Features

- **Machine Learning Models:** A diverse range of algorithms are employed, including:
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Random Forests
  - AdaBoost
  - Gradient Boosting
  - Stochastic Gradient Boosting
  - XGBoost
  - CatBoost
  - Extra Trees Classifier
- **Ensemble Learning:** Hard voting ensemble is implemented to combine predictions from all models, improving accuracy and generalizability across patient populations.
- **Data Preprocessing:** The data is cleaned, normalized, and key features such as age, blood pressure, blood glucose levels, and family history are used to enhance model precision.
- **Performance Evaluation:** Models are evaluated using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC to ensure their effectiveness in predicting CKD risk.

## Dataset

Patient data includes clinical, genetic, and lifestyle factors, allowing for a comprehensive analysis of CKD risk factors.

## Ethical Considerations

The project prioritizes fairness, transparency, and interpretability. Bias mitigation strategies are employed to prevent disparities in CKD predictions across different demographic groups.

## Results

Machine learning significantly outperforms traditional diagnostic methods, providing earlier and more accurate CKD risk predictions. This allows for tailored intervention strategies, improving patient outcomes and reducing the economic burden on healthcare systems.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/arunkumar2645s/CKD_prediction.git
   cd CKD_prediction
   ```
