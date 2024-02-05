# Hand-on ML-projects

This repository contains various data science and machine learning projects that I worked on in my spare time

**1. Prediction for children height**

This project is a modification from the prerequisite assignment for the deep-learning bootcamp from the Erdos Institute. We acknowledge them for setting up the assessment and providing the corresponding data set. 

In part 1 of the assessment, we load the data set, carry out exploratory data analysis (EDA), data visualization, select relevant features, and choose a machine learning model to predict the height of a child. We include the heights of both parents (father, mother), and the sex of the child as the features. We then decide whether interaction terms and regularization are needed in the fitting. Here, I used the following packages and skills:

* Pandas: load and preprocess the data set
* Seaborn: data visualization (pairplot) to choose relevant features and decide if interaction terms are needed
* Scikit-Learn: split the data set into training and test sets, perform a linear regression model to the training set, and evaluate the mean square error (MSE) for both sets
* Analysis: check if the model has overfitting, assess if the model works well from the MSE, and conclude that no regularization is needed
* Prediction: use the model to predict the height of a kid if the heights of the parents are given

In part 2, we use a logistic regression to predict the sex of the child if his/ her height is given. Similar skills to part 1 is applied. Here, we use the receiver operating characteristic (ROC) curve and the area under the curve to assess the model. Again, the fitting and analysis are done using Scikit-Learn.
