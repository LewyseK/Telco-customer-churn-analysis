# Telco-customer-churn-analysis
An ML classification project to analyze the churn rate in a telco.
We use the CRIP-DM framework to establish an optimal model that will predict whether a customer will churn. 
## BUSINESS UNDERSTANDING
**Problem statement** – customers leaving/unsubscribing from the telco services after some time.
**Project aim** – the aim of the project is to find the likelihood of a customer leaving the organization, key indicators of churn as well as some retention strategies that can be implemented to avert this problem.
**Null Hypothesis**- The monthly charges on a customer have no significant effect on whether they will churn.
**Alternative Hypothesis**- The monthly charges on a customer have a significant effect on whether they will churn.
***Key analytical questions***
 1) Which gender is most likely to churn?
 2) Which gender is likely to pay more for the services monthly?
 3) Does the amount a customer is charged monthly have an effect on the contract they procure?
 4) What internet service is most likely to have the most loyal customers?
 5) Which payment method brings in the most revenue?
   
 ## DATA UNDERSTANDING
   This involves importing our libraries for this project. This is followed by loading our datasets and previewing them to know the columns and familiarize with the task.
   The data is then prepared by cleaning some of the columns (Total charges) and aligning the data types.
   An exploratory data analysis is done which includes univariate,bivariate and multivariate analysis to understand the distribution and correlations.
   Various visualizations are created to answer our analytical questions. This aids to better understand our data and some recommendations are made.
   Using the ttest,the hypothesis is tested.
 ## DATA PREPARATION AND PRE-PROCESSING
   The data is split into training and testing data.
   Pipelines for categorical and numerical data are created to transform the data.
   Using 5 models; decison tree, random forest, logistic regression, Kneighbours and SVC performance metrics are compared to get the best performing models.
   The data is balanced and a classification report reveals that randomforest, logistic regression and SVC are the best performing models.
   Cross validation is done, best performing parameters checked and save the trained models.
   The models are then used on our test dataset to make churn predictions.

