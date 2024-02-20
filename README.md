# Monkey-Pox-Prediction
Monkeypox, also known as mpox, is a rare infectious disease caused by the mpox virus. Predominant in Africa, this viral zoonotic disease  include symptoms like fever, headache, muscle aches and backache, swollen lymph nodes, chills and exhaustion. Early and accurate diagnosis is crucial for containment and patient management. With this repository I am joining people in presenting a machine learning model for detecting the monkeypox disease using simple algorithms like KNN, Random Forest and Decision Tree. This model achieves an aggregate accuracy of 76% only. I tried neither fine tuning/ hyperparameter nor deep learning algorithms to enhance the performance of the predictive model. I will update repo once I achieve a higher score of accuracy.

# Data Source
My dataset is already labelled. You can find it in the repo along with the labeling information. The original dataset can be downloaded from here:
https://www.kaggle.com/datasets/nafin59/monkeypox-skin-lesion-dataset/download?datasetVersionNumber=4

# Platform 
Google Colab

# Libraries used
pandas, numpy, matplotlib, seaborn, scikitlearn

# ALgorithms used
KNN, Random Forest and Decision Tree

# Data Preprocessing, Splitting and Model Training
*	Handle missing values
*	Inspect sample column entries
*	Balance target labels if any class imbalances
*	Split training data and test data in the ratio 8:2.
*	Train the training data using the mentioned three ML algorithms

# Model Performance 
*	Evaluated the accuracy, FI score, ROC curve and confusion matrix for each model
*	Got an aggregate score of 0.76


## Conclusion
In this monkeypox detection project, I took a dataset, implemented a conventional training algorit and ended up obtaining an accuracy score of 76%.



