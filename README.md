# classification-challenge

## Background:

The following code is focused on improving the email filtering system for customers by developing a supervised machine learning (ML) model that will accurately detect spam emails in order to filter out customers' inboxes.  The code will generate two classification models to fit the provided data and evaluate which model is more accurate at detecting spam.

The code will require functions, libraries, dependencies, import of a csv file, and regression & classification analysis. 
This code is available at Github under (https://github.com/algjor/classification-challenge).

## Description of Code:
This code was completed using the following steps.

(1) - A repository was created called classification-challenge in Git hub.

(2) - A starter code named spam_detector.ipynb was created on the local Git repository and pushed to GitHub.

(3) - The csv file spam-data.csv was imported for the data analysis from the url https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv.

(4) - The csv file was then loaded into a Dataframe and split into training and testing data sets.

(5) - The label variable was analyzed to get a count of spam vs. legitimate messages.

(6) - The features data was scaled using the X_train & X_test dataframes and transforming.

(7) - A Logistic Regression model was created using the training scaled data, then used to perform testing predictions using test data. 

(8) - An accuracy score comparison was performed to show the accuracy between the y_test (target) and testing predictions using the Logistic Regression model.

(9) - Next, a Random Forest classifier model was created using the training scaled data, then used to perform testing predictions using test data.

(10) - An accuracy score comparison was performed to show the accuracy between the y_test (target) and testing predictions using the Random Forest classifier model.

(11) - The key findings of the data analysis are:

Based on the above analysis using the training data, the Logistic Regression model and Random Forest Classifier model resulted in training data scores of 0.9260869565217391 and 0.9994202898550725, respectively. Therefore, the Random Forest Classifier model outperformed the Logistic Regression model in terms of the training data.  Likewise, the model predictions using the test data accuracy showed a similiar trend in performance between the Logistic Regression model and Random Forest Classifier model with accuracy scores of 0.9348392701998263 and 0.94874022589053, respectively.  Overall, the Random Forest Classifier model is more predictive than the Logistic Regression model in spam detection.
