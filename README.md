## Problem Statement:
An education company named 'X Education' that sells online courses to industry professionals, is targeting to improve its poor lead conversion rate of 30% to around 80% in the future. In order to achieve this target set by its CEO, 'X Education' needs a model to identify the most promising leads or 'Hot Leads'. The model is to be built to assign a score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance.

## Background:
At present, 'X Education' markets its courses on several websites and search engines like Google. Interested professionals land on their website and browse for courses, fill up a form indicating interest in courses or watch some videos. When anyone fills up a form providing their email address or phone number, they are classified as a lead. The company also gets leads through referrals. Once these leads are acquired, the sales team start making calls, writing emails, etc. to convert these leads, to enroll for courses and become paying customers. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. Once they successfully identify this set of leads, the lead conversion rate should go up as the sales team can focus more on communicating with the potential customers and nurturing those leads (i.e. educating the leads about the product, frequently communicating etc.) rather than making calls to everyone.

## Data:
We have been provided with a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t. We need to be mindful of the categorical variables having a level 'Select' which means no input was provided by the leads for those fields and are to be treated as Null value.

## Business Objective:
To build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
The model should be able to adjust to company's requirement changes in the future and handle them as well.

## Approach (or the broad steps are)

1  Reading and Understanding Data
2  Data Quality Checks and Data Cleaning
3  Exploratory Data Analysis
4  Data Preparation
5  Model Building
6  Model Evaluation
7  Summary
