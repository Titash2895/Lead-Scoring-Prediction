# Lead-Scoring-Prediction
This case study helps in predicting whether promising leads are converted into paying customers or not by performing EDA, Statistical Analysis and Model Building
# Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 
The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 
Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.
The company requires to build a model wherein it needs to predict customers which will be converted into paying customers
# Data
You have been provided with a leads dataset from the past with 9240 data points and 37 attributes. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted.
# Project Overview
- We perform EDA, univariate and bivariate analysis to get inferences on the attributes
- Feature selection is done using statistical analysis
- Various models are build and compared. We get the best result in Logistic Regression
- After RFE and implementing HyperParameter Tuning, there is no improvement in the evaluation metrics
- We therefore consider Logistic Regression with its base parameters as the final model
- Metrics score to be considered is Accuracy and Recall
- We need a better recall score and reduce False negatives as predicting a customer as not a potential lead, when the customer actually is a potential lead, results in loss to business
