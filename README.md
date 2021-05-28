# UDACITY Data Science Nanodegree capstone project 
This project is part of UDACITY  Data Science Nanodegree programme. In this project analysis of customer behaviour on the Starbucks rewards mobile app will be presented.
# Motivation
The goal of this project is to find the pattern in the customer behaviour and provide suggestions how to improve the effectiveness of the promotion strategy. Main questions that are addressed in this project are the following:

- Which type of customers spend the most money?
- Which promotion channel is the most effective ?
- Are there any differences in the offer types and completion rate?
In addition, this work aims to buil effective data modelling model in order to predict wether customer will review/complete the order. For this task three different classifiers have been used. Namely, Naive Bayes, Linear Regression and K-Nearest Neighbours. 

# Libraries used
- pandas `import pandas as pd`
- numpy  `import numpy as np`
- seaborn `import as sns`
- json 
- sklearn model selecetion `from sklearn.model_selection import train_test_split` 
- sklearn metrics `sklearn.metrics import confusion_matrix`
- sklearn Gaussian classifier `from sklearn.naive_bayes import GaussianNB`
- sklearn Logistic regression classifier`from sklearn.linear_model import LogisticRegression`
- sklearn KNeighbors classifier`from sklearn.neighbors import KNeighborsClassifier`
- matplotlib.pyplot `import matplotlib.pyplot as plt`

# Files
- Jupyter notebook:\
Starbucks_Capstone_notebook.ipnyb
- README.md:\
Current document.
- Data: \
portfolio.json (List of offers)
profile.json (Customer information)
transcript.json (List of all events)

This data was provided by UDACITY. 
# Summary
This project provided analysis of Starbucks customer behaviour on mobile app. Results suggest that
women and people of 40-60 years old age have the highest offer completion rate. Gaussian (Naive Bayes) classifier works the best for the given problem.
The blogpost about this study can be found here: https://algirdasducinskas.medium.com/how-to-improve-the-starbucks-offer-strategy-f4e93b4734f8

# Author
Algirdas Dučinskas
# Acknowledgements
I would like to give credit  to UDACITY for providing data.
