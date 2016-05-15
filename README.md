# KAGGLE COMPETITION 
###BNP Paribas Cardif Claims Management (30/03/2016)

Kaggle website:
https://www.kaggle.com/c/bnp-paribas-cardif-claims-management

*(Excerpt from the competition)*
###GOAL
In this challenge, BNP Paribas Cardif is providing an anonymized database with two categories of claims:

    claims for which approval could be accelerated leading to faster payments
    claims for which additional information is required before approval

Kagglers are challenged to predict the category of a claim based on features available early in the process, helping BNP Paribas Cardif accelerate its claims process and therefore provide a better service to its customers.

###DATA

You are provided with an anonymized dataset containing both categorical and numeric variables available when the claims were received by BNP Paribas Cardif. All string type variables are categorical. There are no ordinal variables.

The "target" column in the train set is the variable to predict. It is equal to 1 for claims suitable for an accelerated approval.

The task is to predict a probability ("PredictedProb") for each claim in the test set.
File descriptions

    train.csv - the training set including the target
    test.csv - the test set without the target
    sample_submission.csv - a sample submission file in the correct format


