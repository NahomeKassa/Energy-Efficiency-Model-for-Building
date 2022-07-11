# Energy-Efficiency-Model-for-Building
# Predicting two real valued responses (heating vs cooling load) using 8 features

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting the building heating load and cooling load based on the features available.

We're going to take the following approach:

1. Problem definition
2. Data
3. Evaluation
4. Features
5. Importing Libraries 
6. Importing Dataset
7. General Analysis 
8. Data Preprocessing 
9. Modeling 
10. Predicting 

1  Problem definition
How well can we predict the building heating load and cooling load; given its features?

2  Data
The data is downloaded from the Kaggle Bluebook: https://www.kaggle.com/datasets/ujjwalchowdhury/energy-efficiency-data-set?tags=13404-Logistic+Regression

It is also available at UCI machine learning: https://archive.ics.uci.edu/ml/datasets/energy+efficiency

3  Evaluation
The evaluation metrics i will be using for this project are the RMSLE (root mean squared log error), RMSE (root mean squared error), and R^2 (coefficient of determination).

Note: The goal for more regression evaluation metrics is to minimize the error. For example, our goal for this project will be to build a machine learning model which minimizes RMSLE.

4  Features
1. Relative Compactness
2. Surface Area
3. Wall Area
4. Roof Area
5. Overall Height 
6. Orientation 
7. Glazing Area
8. Glazing Area Distribution 

**Predicting**
1. Heating Load
2. Cooling Load


Relevant Papers:

A. Tsanas, A. Xifara: 'Accurate quantitative estimation of energy performance of residential buildings using statistical machine learning tools', Energy and Buildings, Vol. 49, pp. 560-567, 2012



Citation Request:

A. Tsanas, A. Xifara: 'Accurate quantitative estimation of energy performance of residential buildings using statistical machine learning tools', Energy and Buildings, Vol. 49, pp. 560-567, 2012 (the paper can be accessed from [Web Link])

For further details on the data analysis methodology:
A. Tsanas, 'Accurate telemonitoring of Parkinsonâ€™s disease symptom severity using nonlinear speech signal processing and statistical machine learning', D.Phil. thesis, University of Oxford, 2012 (which can be accessed from - http://people.maths.ox.ac.uk/tsanas/publications.htm ) 
