# Credit Card Approval
Predicting if credit card request will approved for the customer given other attributes.

### Motivation
Banking industries received so many applications for credit card request. 
Going through each request manually can be very time consuming, 
also prone to human errors. However, if we can use the historical data to build a 
model which can shortlist the candidates for approval that can be great.

### Libraries Used
  - sklearn
  - pandas
  - numpy
  - seaborn
  - matplotlib

To install the above packages using pip, use command
```$pip install package-name```

### Files Description
- CC_data.csv: This is the dataset file for the project
- Data is downloaded from http://archive.ics.uci.edu/ml/datasets/credit+approval
- CreditCardApproval.ipynb: The jupyter notebook which includes the analysis and modeling

### Usage
  - Run the jupyter notebook CredictCardApproval.ipynb

### Summary
In this project, I have tried to find out the factors that are most important for getting an 
approval for the credit card through the power of Data Analysis and Machine Learning. 
Though we have achieved 86% of accuracy, we also tried to check if we can improve the 
performance further and tried grid search. 
However, 86% is the best we could get from this data using both the model; 
logistic regression and random forest

