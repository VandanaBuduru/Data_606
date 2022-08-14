**The following is the report on he inferences drawn from Exploratory Data Analayasis and Evaluation Metric:**

1)2021, 2018 are the years with most consumer complaints reported.

2)January is month with most consumer complaints reported.

3)2018, 2021 are the years with most consumer complaints settled/resolved.

4)March, January are the months with most consumer complaints resolved.

5)Travel Insurances and Home insurances are the most sought after insurance policies.

6)Disposition type Company Position Substantiated has the highest values in the dataset.

7)The improper claim settlemets are the primary reason for complaint filings.

8)2021 is the year with most complaints filed and 2022 is the year with most of them resolved.

9)Claim handling segment is the most highest segmnet with high recovery amounts then followed by complaints due to marketing and sales segments.

10)2018 is the year with highest sum of claims recovered.

11)February is the Month with highest sum of claims recovered.

12)Compaints are resolved with the highest recovery amounts in Claim handling category.

**Machine Learning Outcomes Evaluation Metric: F-Score**

1) The metrics such as Precision, Sensitivity, Recall, Specificity, F-Score, ROC-AUC Curve is used to evaluate the Classification problem.Here, we could observe that the output data is slightly imbalnced, here we could use the F-1 Score. F-1 score is generally useful when working with the imbalanced dataset and it also combines precision with recall into a single metric.

2) f1_score is 94.1% with Logistic Regression with L2 penalty and AUC value is 96% that implies, the model is 96% accurate in distinguishing the classes.

3) f1_score is 94.1% with Logistic Regression with 10 folds Cross Validation,L2 penalty and liblinear solver.

4) f1_score is 94.1% with Logistic Regression with 10 folds Cross Validation,L2 penalty and Saga solver.

5) f1_score is 99.1% using K-Nearest Neighbours, which is better then Logistic regression.

6) f1_score is 99.1% using Decision Tree, which is better then Logistic regression and K-Nearest Neighbours.

7) f1_score is 99.1% using RandomForest, which is better then Logistic regression and K-Nearest Neighbours and quiet comparable to the decision tree algorithm.

8) f1_score is 99.1% using Xgboost classifier, which is better then Logistic regression and K-Nearest Neighbours and quiet comparable to the decision tree and RandomForest algorithm.

9) f1_score is 96.9% using SVM classifier, which is better then Logistic regression and K-Nearest Neighbours and lower than decision tree, Xgboost and RandomForest algorithm.

10) By comparing all the above implemented models, we can conclude that K-Nearest Neighbours, Decision Tree, RandomForest, Xgboost classifiers has improved the performance of the model and any one of the models can be choosed for prtical business applications.

**Further Improvements and outcomes:**

It's better to have a business understanding of the data and the how seerity the data is. The basic understanding helps in formatting the data and making it suitable for production scale applications and for developing consumer end applications.

Further, the results can be imporved by having vast knowledge on the business doamin, which could be useful in undertsnding and pre-processing the data. Thus, the outliers and any random noise can be removed.

More advanced algorithms like CNN, Neural networks along with Tensor-flow models can imporve the performance of the model.
