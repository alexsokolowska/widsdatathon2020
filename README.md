# WiDS Datathon 2020 (Kaggle Competition) 

https://www.kaggle.com/c/widsdatathon2020/overview


The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT’s GOSSIS community initiative, with privacy certification from the Harvard Privacy Lab, has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year timeframe. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States.

This notebook presents a step-by-step solution to the data science competition by Women in Data Science Datathon 2020.

1. Data pre-processing: handle missing values, perform categorical encoding.

2. Data exploration: explore relationships, select features.

3. Modelling - design a neural network, try various classifiers, model evaluation, ROC curve.

4. Hyperparameter tuning - select the best model with grid search, random search. 

*Accuracy on the validation set: 0.9297.*
AUC-ROC on the test set: 0.8854289224151952
*Result on 50% of the test data used in the kaggle competition: 0.87072.*