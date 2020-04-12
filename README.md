# Modeling-Neural-Network
Prediction of structure in the atmosphere given radar returns targeting free electrons in the ionosphere

It is a binary classification problem
There are 34 independent variables.
All of the independent variables are integers/real.
Dependent variable (class label) is categorical (with values 'g' or 'b').
There are no missing values.
We will encode the class label (dependent variable) to convert categorical values to numerical values.
We will do feature scaling to standarise the feature values with mean as zero and std. devation as one.
Model the prediction by building a nerual network using keras.
Evaluate the model using cross validation methods(k-fold)
Print the accuracy and the confusion matrix.
