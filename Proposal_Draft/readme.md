## Title: 

This project aims at building a complete data science project which analyzes the listing of consumer complaints filed against Insurance companies licensed in Connecticut. This dataset includes the Company, Line of Business, nature of complaint, outcome or resolution, and recovery.

This application can be used by any agency,  Insurance industry stakeholders, or the general public to predict the status of consumer filings against the insurance companies.

This is a complete data-driven application that considers the existing data to predict the Status of the Consumer complaints.

![image](https://user-images.githubusercontent.com/103658312/172515384-1771d091-78b9-47e4-838c-896d7c9639a5.png)


**Background Information:**

The insurance industry and the concept of insurance have penetrated the lives of the people so deeply that it become an essential part of everyone's lives either to protect their families, business, or personal lives from unforeseen financial damages or problems. 

As the population is growing and the impact of education has offered everyone to evolve and upgrade their lives constantly. To have a balanced life, it is imperative to have the risk calculation in place. Insurance is one such kind of industry that offers the option of risk aversion. As the population is growing at an alarming rate, the insurance filings and the problems with the insurance policies is increasing at exponential rates. This project aims about understanding the insurance domain and the necessary data science steps to build the application.

**Problem Intensity:**

The intensity of the risk is growing as the world is advancing in globalization. With the increase in risk, it is quintessential to protect from unforeseen damages. Yes, it is common that as the insurance policies grow linearly, the associated problems in the policies grow at exponential levels.

![image](https://user-images.githubusercontent.com/103658312/172515514-9113472e-b3df-46fe-bc84-fa95390d450a.png)

**Existing problems in the Insurance Sector:**

1. Growing Cyber Risk: The risk of data privacy is a common problem in the insurance industry.

2. The high level of insurance technology.

3. Trust Issues between the insurer and the insuree.

4. Growing insurance players in the market.

5. Poor Administration 

6. Economic Instability.

Goals of the project:

To develop an end-to-end data science application that is used by any insurance industry stakeholders to predict the status of the problem status regarding their insurance policy issues.

To develop a comprehensive business understanding of the insurance industry and identification of problems that can be addressed by using data science practices.

![image](https://user-images.githubusercontent.com/103658312/172515579-0270698f-53dd-4efc-ba3b-ce2b7287775e.png)


This project narrows the gaps between the insurer and insuree by addressing their problems and helping the insurance companies to cut the costs on their customer operations team that is served o address the problems faced by consumers. This could save a huge amount of capital for the insurance companies.

**Dataset Description:** 

Number of features: 12

List of features: ['Company', 'File No.', 'Opened', 'Closed', 'Coverage', 'SubCoverage',
       'Reason', 'SubReason', 'Disposition', 'Conclusion', 'Recovery']
       
 Target Variable : Status

Company: Name of the Insurance Company

File No.: Consure problem primary identification number

Opened: Date on which the complaint is registered

Closed: Date on which the complaint is resolved

Coverage: Either Group/Individual Coverage

Sub-Coverage: Specific Coverage types like health, dental, life, etc.

Reason: The broad reason for the insurance complaint

Sub_Reason: The reason for the insurance complaint at the low granular level

Disposition: Disposition of the claim or policy

Recovery: Amount recovered by the claim

Status: Current Status of the insurance complaint

**Data Source:**

https://data.ct.gov/Business/Insurance-Company-Complaints-Resolutions-Status-an/t64r-mt64

Unit of Analysis: Each consumer complaint/claim

Number of Observations: 24398

Output Variable: Status of the Complaint/claim

**Steps performed and Models Used:**

![image](https://user-images.githubusercontent.com/103658312/172515638-c06846f5-c3ab-47ee-8301-ccc3ff7dd1bd.png)


1. Simple Logistic Regression

2. Logistic Regression with Various Penalties.

3. Logistic Regression with Various Penalties at various regularization strengths and using different solvers.

4. Support Vector machine algorithms.

5. K - Nearest Neighbors algorithms.

6. Adaboost Algorithm.

7. Decision Tree

8. Decision trees with various hyper parameters

9. Ensemble models.

**Model Performance Comparisons:**

Though there are several parameters to compare the model performances like Precision Score, Recall, Accuracy, F-1 Score, Confusion Matrix, Area Under the Curve Score, ROC_AUC Score, and Specificity, I would identify the best parameter to compare the machine learning models on the business understanding and the quality of the data involved.
 

**Expected Outcomes of the Project:**

1. Understanding of Hypothesis Testing Scenarios.

2. Understanding of Various data cleaning activities.

3. Understanding of Various data imputation techniques.

4. Outliers' treatment

5. Accuracy & Precision Trade-off.

6. Implementation of Various Statistical Analysis.

7. Dimensionality Reduction and Principal Component Analysis.

8. Usage of Various Machine Learning Algorithms.

9. Understanding of Exploratory Data Analysis.

10. Understanding of Story Telling activities in data science.

11. Recording and Reporting of performances of various models.

