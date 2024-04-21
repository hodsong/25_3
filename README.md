# PROJECT TITLE 


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
100 words to explain what your project is about to a general audience.

Industry Problem Statement : Effectively predicting and reducing legal and regulatory, operational and brand risk by accurately analysing management capabilities and maturity levels in Governance, Risk Management, Compliance, Architecture, Information Security and Audit.
Output : Maturity risk score i.e., analogous to a credit risk score

The industry problem would be based on machine learning and artificial intelligence work in understanding credit risk assessment.
The data available for the industry problem may be limited, with limited or no capability and maturity scores for different organisations within the group.
The project will therefore look at existing data and models for assessing credit risk in rural India where previous risk scores and credit ratings for loanees may not exist, i.e. Unlocking Opportunities: Exploring Credit and Loan Dynamics in Rural India.

Although originally from a development background (MCSD, MCSD.NET, MT) across multiple platforms and the full development stack, the purpose of taking the Imperial College course has been to reinforce an understanding of the technical principles of machine learning and artificial intelligence to allow for its appropriate Governance, Risk Management and Compliance to laws and regulations.

A baseline pre-existing code model has therefore been selected that will be reviewed and further optimised.

## DATA
A summary of the data you’re using, remembering to include where you got it and any relevant citations. 
The dataset used will be the Rural Credit Dataset [/kaggle/input/creditloan-dataset-rural-india/RuralCreditData.csv](https://www.kaggle.com/datasets/heydido/creditloan-dataset-rural-india)

Datasheet : https://github.com/hodsong/25_3/blob/main/data_sheet.md
Licence : https://www.mit.edu/~amini/LICENSE.md

## MODEL 
A summary of the model you’re using and why you chose it. 

Based on learning outcome 'LO 1:optimise an existing code base' listed in 25-3 a baseline model will be based based on the pre-existing code in 
python notebook eda-fe-modeltraining-loan-dataset-rural-india.ipynb (Aashish Jaiswal - This Notebook has been released under the Apache 2.0 open source license). This notebook has been renamed 25-3 Baseline Model.pynb in the GitHub repository. To run this code the Anaconda environment required an command line update i.e., conda install -c conda-forge xgboost.

Baseline Model : Random Forest Regressor
Baseline Notebook : https://github.com/hodsong/25_3/blob/main/25-3%20Baseline%20Model.ipynb

This baseline model will be changed, further reviewed and optimised in an attempt to improve on performance.

Model Card : https://github.com/hodsong/25_3/blob/main/model_card.md

## HYPERPARAMETER OPTIMSATION
Description of which hyperparameters you have and how you chose to optimise them. 

Additional information is included in the respective notebooks.

Baseline Python Notebook : max_depth, max_features, min_samples_leaf, min_samples_split, n_estimators, random_state

Optimised Python Notebook :

## RESULTS
A summary of your results and what you can learn from your model.

Additional information is included in the respective notebooks.

Baseline Python Notebook : The most effective model in making predictions is the Random Forest Regressor Model optimised with hyperparameters 
{'criterion': 'absolute_error', 'max_depth': None, 'max_features': None, 'min_samples_leaf': 2, 'min_samples_split': 5, 'n_estimators': 10, 'random_state': 42}

Optimised Python Notebook :

You can include images of plots using the code below:
![Screenshot](image.png)

## (OPTIONAL: CONTACT DETAILS)
If you are planning on making your github repo public you may wish to include some contact information such as a link to your twitter or an email address. 

