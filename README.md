# machine-learning-challenge

This project aims to test and tune different classification models using machine learning.
The data used in this project is from NASA Kepler space telescope to discover hidden planets outside the solar system.
The machine learning model must be able to classify candidate exoplanets from raw dataset.

Data is preprocessed before fitting the model. Features necessary are selected and the rest are removed. Numerical data are scaled.  
Data is separated into training and test data. 

Once data is ready, models are tuned using GridSearch using two different classifiers: Logistic Regression and SVM.
The results between the two models are compared.


