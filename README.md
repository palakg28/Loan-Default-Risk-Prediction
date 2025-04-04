Introduction

Defining Problem statement - 
Retail banks rely heavily on home loan interest as a primary revenue source. However, the presence of non-performing assets (NPAs)—loans that default—poses a major risk to profitability. To ensure sustainable lending practices, banks need a robust and data-driven approach to assess loan applicants effectively.
This project aims to develop a classification model that leverages machine learning techniques to analyze past loan data and identify key factors influencing loan defaults. By training on historical applicant data, the model will help banks make informed, evidence-based decisions on loan approvals, reducing financial risk while improving efficiency and fairness in the lending process.

Need of the study/Project - 

This study is needed to help banks improve their loan approval process and avoid financial losses due to non performing assets. 
Adopts the Equal Credit Opportunity Act by making sure the approval process is free of biases and wrong judgment/human error.

Understanding business opportunity - 

Faster and more efficient loan approval process of lending home credit loans
Higher profits for banks after recognizing ‘bad loans’

 Understanding social opportunity - 

Gives everyone a fair and equal chance to apply for a home credit loan free of human errors, wrong judgement and biases



Data Report

This dataset consists of previous loan applications to the bank, categorized in terms of good(loan repaid) or bad(client defaulted). 

Time/Frequency -

Data was collected over a certain period of time of applications and the frequency of data entry varies. None of these are explicitly mentioned in the dataset, so could be of varying value.

Methodology - 

The data has been collected through previous loan application taking in account the customer’s 
financial records such as current income, debt, job etc.

Visual Inspection of data

Rows - number of rows is the total number of loan applications that have been recorded (including both good and bad ones)

Columns - Total number of columns are 13, for the attributes on which the data is studied.

Descriptive details - Making sure everything is consistent, by identifying outliers, and checking for missing values.


Plan of Action for the Model
Exploring the Dataset:
I will thoroughly analyze the dataset to identify any additional features that can enhance the prediction of loan approval. This could involve creating new features, such as more ratios to uncover patterns that relate to the target variable (loan).
The data will be examined for compliance with the Equal Credit Opportunity Act's guidelines to ensure that no protected characteristics (like race or gender) are unfairly influencing the model's predictions.
I will evaluate the importance of each feature to understand which ones have the strongest impact on predicting loan approvals or rejections.
Model Selection:
My goal is to classify applicants as either good or bad borrowers based on their creditworthiness. This classification will determine whether they will be/should be approved or rejected for a loan.
I wish to use classification models such as Logistic Regression, which can provide a good balance between predictive performance and interpretability.
Training and Testing the Model:
I will split the dataset into training and testing sets. The model will be trained on the training data, and its performance will be evaluated on the testing data.
The training process will focus on generating a model that can accurately predict whether an applicant should be approved or rejected for a loan.
The final model will be assessed for interpretability, ensuring that it can justify rejections by identifying the key features that led to those decisions.
