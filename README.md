# FakeJobPrediction

## Abstract

Identifying fake job postings and real job postings on the web is a big challenge. This is a binary classification problem which can be solved using Machine Learning. In this project, the class in the normal state is the real job postings when compared to the fake ones which fall under the abnormal state. The most popular machine learning algorithms that can be used for binary classification include Logistic Regression, k-Nearest Neighbors, Decision Trees, Support Vector Machine, Naive Bayes, etc. We shall design, develop and implement the models best suited for this classification and find the best model based on a series of machine learning metrics. 
When solved it can help innocent people who are preyed upon by avoiding scams. With the help of this application, one can be educated and made aware of a possible fraud preying on personal information and resources, making society a safer and secure place.

## Instruction
### For Pickled Models
Run the following lines: <br />
pickled_model = pickle.load(open('modelName.pkl', 'rb')) <br />
'model'_pred = pickled_model.predict(X_test)
