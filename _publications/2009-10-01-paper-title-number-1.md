---
title: "Infosys Limited [ AUG 2013 - DEC 2015]"
collection: publications
permalink: /publications/2009-10-01-paper-title-number-1
---
At Infosys, I worked for a European banking client on projects related to Data Analysis and Machine Learning. I have experience working on different phases of end to end pipeline under the supervision of Data Scientists, such as <br/>
​
Requirements: Communicated with client and Subject Matter Experts to identify and document business needs and problem statements that require data driven solutions<br/>
Data Extraction: Used SQL,PL/SQL, Hive query language to obtain data required for analysis from multiple sources such as Oracle DB, Hive tables<br/>
Data Preparation: Used R packages such as dplyr, tidyr, lubridate for data preparation activities such as data cleaning,dealing with missing values,parsing the dates,creating new variables ,regular expressions to process text etc.<br/>
Data Exploration: Used R packages ggplot2 , pca, alr4,dplyr to check distributional assumptions using statistical tests,for obtaining summary statistics and aggregated tables, checking associations among variables using correlation analysis/plots and removing high correlations in data, principal component analysis for dimensionality reduction etc.,<br/>
Model Building: Used CARET,h20 packages in R to train different supervised learning models on data such as Regression, Logistic regression, Decision Tree, Random forests and methods such as cross validation,regularization to deal with over fitting<br/>
Reporting: Presented and discussed the data driven model results with non technical audience (client) to identify the factors that can help in business decision making.<br/>
​
During the course,I got the opportunity to work on several projects and learnt many things like text mining methods,HIVE and core banking domain.Below are details about two major projects,<br/>

Loan Defaulter Prediction: <br/> 
The objective of this project is to predict whether a customer of the bank will default or not in near future, and help the bank to make a decision in the approval process of loan.<br/>
Identified the key variables for analysis by working together with banking domain Subject Matter Expert (SME) and documented the requirements
Studied the schema of database and wrote SQL queries to pull data from several tables in order to compile data set for the analysis<br/>
Performed data cleaning and manipulation such as deleting records with majority missing columns,created new variables from existing variables like maximum transaction amount,discretized income etc.,<br/>
Hand annotated response classes "Default","Non Default" for a sample of customer records using the business rules to create training labels
Explored several attributes of customer such as age,income,number of loans,sex,credit score  etc., w.r.to response variable<br/>
Modeled logistic regression for the classification to interpret the variable importance based on odds ratio and decision tree model to interpret variables ,derive decision rules based on tree structure
Evaluated model performance based on F1-Score and tree model outperformed logistic model ,hence as a next step Random Forest model was trained to achieve better results<br/>
Tested the model performance on future loan data, both logistic regression and Random forest achieved better F1 score than expert judgement by 0.15 this is because existing expert judgement over looked some dynamic variables like late fee<br/>
​
Customer Sentiment Analysis:<br/>
Goal of this project is to build a classification model to categorize customers into "Happy" or "Unhappy" categories.
Data was queried using SQL and complied data set for the analysis with email text, survey feedback and target sentiment variable
Performed Feature engineering,data cleaning on email text,survey feedback in two steps<br/>
i) For the email text used text mining methods such as regular expressions, tf-idf to convert raw text to numeric vectors and then used PCA (Principal Component Analysis) to obtain dense representation of features.<br/>
ii) For the survey feedback,it represents scores to a set of questions in the range of 0-7  and this data has high proportion of missing values ,to handle missing data used NNMF (Non negative matrix factorization) to fill the missing scores.<br/>
and later both these feature sets were combined with target variable to obtain training data set.<br/> 
Modeled logistic regression for the binary classification of sentiment and to deal with over fitting techniques such as cross validation and regularization(LASSO,Ridge) were considered, used Accuracy as model evaluation metric.<br/>
Interpreted variable selection using odds ratio and LASSO model to find out influential variables and it turns out that some of the survey feedback variables are important in classifying sentiment where as the dense features from text could not be interpreted as they are the principal components.<br/>
​Obtained the best model that has better accuracy and predicted sentiment on unseen customer data.<br/>
​
​​
Apart from work routine, I delivered training sessions to peers on technology such as SQL,Big Data Basics and for the best efforts as a team player I was honored with "INSTA AWARD". After exhilarating 2.5 years in the job ,I decided to pursue Masters degree in Analytics at the University of Illinois at Urbana champaign to gain next level expertise in Data Analysis and Machine Learning.<br/>
​
​