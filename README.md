# Supervised Machine Learning Homework - Predicting Credit Risk


#About This Repository
In this repository is a jupyter notebook with diplaying the models tested. Also there is CSV file with the loan data used in the models, and a PDF of the *revised* rubric for this homework challenge. 


#About The Assignment 
In this assignment, I built a machine learning model that attempts to predict whether a loan will be approved or not. I compared the Logistic Regression model and Random Forest Classifier.

#Hypothesis 
My hypothesis is the Random Forests Model will perform on the data due to two reasons. First, random forests resamples the large data set for each new decision tree and secondly the decision trees for Random Forests choose the optimal split point for each decision, therefore it will most likely be more accurate. 

#Conclusion 
After testing both models,my hyothesis was incorrect. The Linear regression model was a better fit for my dataset.  While the random trees had a slighly higher training score, the Linear Regression model had a difference of .0003 between the test and training score while the random trees model had a .006 difference. The larger variation in the Random trees model can be attirubuted to being slighlt overfit. Logistical regressions do better with datasets when the number of noise variables is less than or equal to the number of explanatory variables.


