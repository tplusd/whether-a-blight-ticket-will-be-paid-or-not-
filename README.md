# whether a blight ticket will be paid or not?
This project is based on a data challenge from the Michigan Data Science Team(MDST). It is also a final project from the coursera online course, Applied machine learning in Python from University of Michigan. The Michigan Data Science Team (MDST) and the Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS) have partnered with the City of Detroit to help solve one of the most pressing problems facing Detroit - blight. Blight violations are issued by the city to individuals who allow their properties to remain in a deteriorated condition. Every year, the city of Detroit issues millions of dollars in fines to residents and every year, many of these fines remain unpaid. Enforcing unpaid blight fines is a costly and tedious process, so the city wants to know: how can we increase blight ticket compliance? So the first step in answering this question is understanding and predicting whether a resident may fail to comply with a blight ticket. The dataset is provided by the Detroit Open Data Portal.

This projects can be divided into several parts:
1.Data extraction,cleaning,and visualizaion of the training and test datasets.
2.Feature engineering.Discarded unnecessary features. Used feature importance in random forest to
select important features.
3.Fitted a gradient boosting model for the training data, and did grid search to find
optimal parameters.
4.Used the optimal parameters to predict the label and therefore classifiy the test set into two groups.
Plotted the roc curve of training data.
