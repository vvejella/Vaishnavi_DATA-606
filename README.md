# DATA-606 CAPSTONE PROJECT
### LOAN DEFAULT PREDICTION
> What is your issue of interest (provide sufficient background information)?

Loan lending has been an important part of daily lives for organizations and individuals alike. With the ever-increasing competition in the financial world and due to a significant amount of financial constraints, the activity of taking a loan has become more or less inevitable. Individuals around the world depend on the activity of loan lending for reasons such as overcoming their financial constraints in order for them to achieve some personal goals. Similarly, banks, small to large firms depend on the activity of loan lending for the basic purpose of managing their affairs and to function smoothly in times where there are financial constraints.

> Why is this issue important to you and/or to others?
----------------

> What questions do you have in mind and would like to answer?
--------------

 We want to help the lenders or banking institutions to evaluate their customer and predict the  --------------------
 
> Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?

We found the dataset from Kaggle. The size of dataset is 28MB which contains 34 columns namely ID, year, loan_limit, gender, approv_in_adv, loan_type, loan_purpose, Credit_Worthiness, open_credit, business_or_commercial, loan_amount, rate_of_interest, Interest_rate_spread, Upfront_charges, term, Neg_ammortization means 
Negotiative ammortization, interest_only, lump_sum_payment, property_value, construction_type, occupancy_type, Secured_by, total_units, income, credit_type, credit_score, 
co-applicant_credit_type, age, submission_of_application, LTV, region, Security_Type, status, dtir_1.
##### Data source- https://www.kaggle.com/yasserh/loan-default-dataset


> What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?

 Banking customer is the unit of analysis.
 We want to analyze about 148671 observations.
 
> What variables/measures do you plan to use in vour analysis (variables should be tied to the questions in #3)?

Loan status------------------

> What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?

Random Forest with Randomized search CV, Logistic Regression with Grid search CV, Support Vector Machine with Grid search CV, K Nearest Neighbors with Grid search CV, Bagging with Base estimator as Random Forest, Bagging with Base estimator as Logistic Regression, AdaBoost Classifier, MultilLayer Perceptron Classifier.

> How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?

We are planning to evaluate the metrics such as recall, accuracy, precision, f-1 score, confusion matrix, ROC-AUC scores. After detriming the metric to evaluate the model with the help of the business understaing of the domain of the data, we'll figure out the ways to imporve the performance of the model.

> What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?

Importnace of business domain understanding in chossing and evaluating the model.
To apply various machine learning models to classify the outcome.
Usage of Various evaluating metrics to determine the performnace of the model.
Importance of Various Statistical Analysis
Understanding the Dimensionality Reduction.
Understanding the Bias-Variance trade-off.
Application of Prinicipal component analysis.
Usage of Grid search Validations.
Understanding of Various actification functions. 
Effectively handling the outliers.
Usage of various hyper parameters.
Analyizng & Visualizing the data.

