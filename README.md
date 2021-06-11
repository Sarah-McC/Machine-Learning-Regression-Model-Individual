# Machine-Learning-Regression-Model-Individual
In this assignment, you are tasked with using the information in our course case to build a predictive model on a continuous response variable (Y-variable). This assignment encompasses feature engineering, model preparation, variable selection, and model development.   

Criteria 1 – Train-Test Gap

Gap between training and testing scores must be less than or equal to 0.05. In train-test split, make sure your random_state is set to 219 and your test_size is set to 0.25.

 

Violation Penalty

If the gap is greater than 0.05, your final model points will be reduced by the amount of the gap that exceeds 0.05. For example, if the train-test gap is 0.06, your final model points will be reduced by 0.01.

If your random_state is not set to 219 or your test_size is not set to 0.25, this will be manually adjusted when your deliverable is being graded and your final model points will be reduced by 0.25.

 

 

Criteria 2 – Response Variable Usage

The response variable cannot used in any form as an explanatory variable (the Y-variable cannot be used on the X-side).

 

Violation Penalty

Both of the following will occur if the response variable was used as an explanatory variable:

The model will be rerun after this variable has been removed.
Your final model points will be reduced by 0.025.
 

 

Criteria 3 – Model Types

Model types are appropriate for the task at hand and come from statsmodels or scikit-learn (other packages and engines are not permitted).

 

Permitted Model Types

OLS Regression (standard linear regression)
Lasso Regression
Bayesian Automatic Relevance Determination (ARD)
K-Nearest Neighbors Regression (KNN)
 

Note that you are permitted to adjust the optional arguments of the permitted model types.

 

Violation Penalty

Final models that are not in the list of permitted model types will be discarded and the last appropriate model that ran in your code will be used as your final model. Final model points will be reduced by 0.025.

 

 

Criteria 4 – Code is Well-Commented and Runs Without Errors

For this assignment, aim for a minimum one quality comment for every 10 lines of code. Note that this criterion is less strict than in the Python for Data Science course as you have developed further in your coding journey.

 

Violation Penalty

Not being well-commented will reduce your final model points by 0.025.
Submitting a code with at least one error will reduce your final model points by 0.025.
 

 

Criteria 5 – Code Processing Speed

Your code must process from beginning to end in 60 seconds or less, based on your computer’s processing speed.

 

Violation Penalty

Not being well-commented will reduce your final model points by 0.025.
Submitting a code with at least one error will reduce your final model points by 0.025.
 

 

Criteria 6 – Model Output

Output table of candidate models is well-formatted and contains the following information:

Model Type
Training Score
Testing Score
Train-Test Gap
Model Size (number of variables used plus the intercept)
Model Coefficients and Variables (when applicable)
It is clear which model is your final model (label it accordingly)
 

Violation Penalty

Not including all of the above information in a well-formatted table (as presented in class) will result in a 0.25 reduction in model points.

 

If it is unclear which model was selected as the final model, the following will occur:

1 grade band reduction for this part of the rubric.
The last model in the candidate model output will be utilized.
