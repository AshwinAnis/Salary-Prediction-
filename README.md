# Salary-Prediction-
The objective of this analysis is to fit and compare 4 different models to predict the salaries offered by various data science job positions using the data collected from job ads posted on glassdoor by several US compaines.
Various regression models like multi-linear model, Ridge model, Lasso model, Support vector regressor
model and Random Forest models were considered for training.
Random Forest regressor turned out to be best with lowest MAE among the other models while support
vector regression was the worst performing model for this dataset.
Random forest regressor was further fine-tuned by using GridSearchCV method to find the optimal
parameters.
This model predicts with an accuracy of 65% on the un-seen data.
