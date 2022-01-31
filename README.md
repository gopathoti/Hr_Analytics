# Hr_Analytics

Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right
people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

1.They first identify a set of employees based on recommendations/ past performance.

2.Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical.

3.At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than
60% are considered) etc., employee gets promotion.

For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence,
company needs help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

# EDA 
-->This train dataset consists of total 54808 rows and 14 columns

-->And there are some null values found in two columns. imputed those null values with MODE.

-->All category and object columns have been seperated so as to perform label encoding.

-->Some important variable analysis is also done by using:

    1.Ttest

    2.F_oneway

-->And this data was IMBALANCED.

-->So balanced the data using SMOTE , so thatwe can achieve good F1_score,Precision and recall values.

-->Then Logistic regression and Random Forest models were built on it.

-->Random forest gave the best results with accuracy of 97% and a very good classification report.

-->Comparetively Random forest predicted less false positives and false negatives than logistic regression.
