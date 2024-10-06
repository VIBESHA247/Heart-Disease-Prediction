Heart Disease Prediction


This project focuses on building a machine learning model to predict heart disease based on a dataset of patients' health metrics. The goal is to classify the presence or absence of heart disease using various machine learning algorithms.


Requirements

The project is implemented in Python, using the following libraries:

  1. pandas
  2. numpy
  3. scikit-learn

Install the required packages using the following command:

pip install -r requirements.txt

Notebook Overview

1. Data Exploration: The dataset is first explored to understand its structure, types, and statistics.
2. Data Preprocessing: Features are prepared for model training by encoding categorical variables and normalizing numerical values.
3. Model Training: Several machine learning models are trained, including:
      Random Forest Classifier
      Extra Trees Classifier
      Voting Classifier (an ensemble of multiple models)
4.Evaluation: The models are evaluated based on accuracy, precision, and recall metrics.


Results


The models are evaluated using accuracy, precision, and recall. The Random Forest and Extra Trees models showed promising results in predicting heart disease. The ensemble model (Voting Classifier) helped in improving the overall performance.

Future Improvements


  1.Hyperparameter tuning to further improve model accuracy.   
  2.Experimenting with other advanced machine learning algorithms like Gradient Boosting.    
  3.Incorporating feature selection techniques to reduce dimensionality and improve performance.
