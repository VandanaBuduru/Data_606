**Introduction**

The insurance industry and the concept of insurance have permeated so profoundly in and out of 's relationships that they have become an essential part of everyone's lives, whether to protect their families, businesses, or personal lives from unforeseen financial damages or problems.

As the population grows, so does the impact of education, which allows everyone to change and evolve and upgrade their lives. It is essential to have a risk calculation in place in order to live a balanced life. Insurance is one such industry that provides the option of risk avoidance. As the population grows at an alarming rate, insurance filings and problems with insurance policies grow at an exponential rate. This project seeks to comprehend the insurance domain and the necessary procedures.

![image](https://user-images.githubusercontent.com/103658312/185778897-91176fde-e6c8-4f85-ba16-61a382b384bb.png)

**Youtube Video Link**

https://youtu.be/LjdxQybmr_A

**PPT**

https://github.com/VandanaBuduru/Data_606/tree/main/FInal_Presentation

**Source Code of the Project**

https://github.com/VandanaBuduru/Data_606/blob/main/Final_Project/Data_606_FinalProject_Vandana.ipynb

**Main Problem in the Insurance Sector**

As the world will continue to broaden, the danger becomes more intense. With the increase in risk, it is critical to protect against unforeseen damages. Yes, it is common for insurance policies to grow linearly while the associated problems in the policies grow exponentially

![image](https://user-images.githubusercontent.com/103658312/185778946-6ebefd0e-27a8-458e-bd6a-8bd03bc8c2e5.png)


**Main Goal of the project**

This project aims to create a complete data science project that analyses the list of consumer complaints filed against Connecticut-licensed insurance companies. This dataset contains information about the company, the line of business, the nature of the complaint, the outcome or resolution, and the recovery.
Any agency, Insurance industry stakeholders, or the general public can use this application to predict the status of consumer filings against insurance companies.
This is a fully data-driven application that analyses existing data to forecast the status of consumer complaints.

**Research Process**

I have implmented the project as in below mentioned steps:

1)Defining the goal

2)Getting the data 

3)Cleaning the data

4)Enriching the data

5)Finding Insights and visualize

6)Deploying Machine Learning algorithms 

7)Drawing Inferences 

![image](https://user-images.githubusercontent.com/103658312/185779136-831eb987-cbe4-474f-9fe6-0b5d59528321.png)


**Technologies Used**

Python,Machine Learning 

![image](https://user-images.githubusercontent.com/103658312/185779166-7d217afa-cbdd-4d8a-bb68-ad0262c8a939.png), 


**Machine Learning Algorithms implemented**

1)Logistic Regression

2)Logistic Regression using Grid Search CV at various regularization strengths and liblinear solver

3)Logistic Regression using Grid Search CV at various regularization strengths and saga solver

4)K-Nearest Neighbour 

5)Decision tree 

6)Random Forest

7)Xgboost 

8)SVM

![image](https://user-images.githubusercontent.com/103658312/185779330-da6f0bdf-f84d-4530-81f0-a64bfc33b1de.png)

**Evaluation Metric**

![image](https://user-images.githubusercontent.com/103658312/185779377-50526d61-ee51-4781-bacb-e0181f9f13fa.png)

I have chosen F1-Score as evaluation metric 


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

**Machine Learning Outcomes Evaluation Metric: F1-Score**

1)The metrics such as Precision, Sensitivity, Recall, Specificity, F-Score, ROC-AUC Curve is used to evaluate the Classification problem.Here, we could observe that the output data is slightly imbalnced, here we could use the F-1 Score. F-1 score is generally useful when working with the imbalanced dataset and it also combines precision with recall into a single metric.

2)f1_score is 94.1% with Logistic Regression with L2 penalty and AUC value is 96% that implies, the model is 96% accurate in distinguishing the classes.

3)f1_score is 94.1% with Logistic Regression with 10 folds Cross Validation,L2 penalty and liblinear solver.

4)f1_score is 94.1% with Logistic Regression with 10 folds Cross Validation,L2 penalty and Saga solver.

5)f1_score is 99.1% using K-Nearest Neighbours, which is better then Logistic regression.

6)f1_score is 99.1% using Decision Tree, which is better then Logistic regression and K-Nearest Neighbours.

7)f1_score is 99.1% using RandomForest, which is better then Logistic regression and K-Nearest Neighbours and quiet comparable to the decision tree algorithm.

8)f1_score is 99.1% using Xgboost classifier, which is better then Logistic regression and K-Nearest Neighbours and quiet comparable to the decision tree and RandomForest algorithm.

9)f1_score is 96.9% using SVM classifier, which is better then Logistic regression and K-Nearest Neighbours and lower than decision tree, Xgboost and RandomForest algorithm.

10)By comparing all the above implemented models, we can conclude that K-Nearest Neighbours, Decision Tree, RandomForest, Xgboost classifiers has improved the performance of the model and any one of the models can be choosed for prtical business applications.

**Further Improvements and outcomes:**

It's better to have a business understanding of the data and the how seerity the data is. The basic understanding helps in formatting the data and making it suitable for production scale applications and for developing consumer end applications.

Further, the results can be imporved by having vast knowledge on the business doamin, which could be useful in undertsnding and pre-processing the data. Thus, the outliers and any random noise can be removed.

More advanced algorithms like CNN, Neural networks along with Tensor-flow models can imporve the performance of the model.
