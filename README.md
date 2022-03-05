# Neural_Network_Charity_Analysis

## Overview of the analysis

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

-EIN and NAME—Identification columns\
-APPLICATION_TYPE—Alphabet Soup application type
-AFFILIATION—Affiliated sector of industry
-CLASSIFICATION—Government organization classification
-USE_CASE—Use case for funding
-ORGANIZATION—Organization type
-STATUS—Active status
-INCOME_AMT—Income classification
-SPECIAL_CONSIDERATIONS—Special consideration for application
-ASK_AMT—Funding amount requested
-IS_SUCCESSFUL—Was the money used effectively

This analysis consists of three technical analysis deliverables and a written report. 
Deliverable 1: Preprocessing Data for a Neural Network Model
Deliverable 2: Compile, Train, and Evaluate the Model
Deliverable 3: Optimize the Model


## Results:

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
>Application types 

What variable(s) are considered to be the features for your model?
>AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION,STATUS, INCOME_AMT,SPECIAL_CONSIDERATIONS, ASK_AMT

What variable(s) are neither targets nor features, and should be removed from the input data?
>PII such as EIN and name. 


### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
>I tried many different combinations, but for the best performed one, with the accuracy of 72.58%, I used 8 neurons and 5 layers, first 2 activation functions are "relu" and the last one is "sigmoid". I chose such just from my experience and repeated testing.


Were you able to achieve the target model performance?
>No, not higher than 75%


What steps did you take to try and increase model performance?\
>I tried many different combinations. Interestingly, after I added the check points, the performance actually went up from 53% to 72.58%. 



## Summary:

The deep neural network machine learning model produced fine results, after trying different hidden_nodes_layer combinations, the best accuracy I got was 0.7258. However, the accuracy never reached above 0.75, even after 10 more optimization tests. 
It might worthwhile to try other activation type other than "relu" and "sigmoid", or not use deep learning but other types of machine learnings.  