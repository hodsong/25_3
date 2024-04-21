# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

- For what purpose was the dataset created? 
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?

'One of the metrics used by banks to check credit worthiness of an individual is credit score, but for people who have never taken a loan in the past don't have a credit score in first place, and it becomes difficult for banks to lend them.
The "Credit/Loan Dataset - Rural India" is a collection of data points of individuals without a prior credit score and the loan amount sanctioned to them.
The dataset can be used to train models to check the eligible loan amount.'

## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 
- How many instances of each type are there? 
- Is there any missing data?
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?

'The "Credit/Loan Dataset - Rural India" is a collection of data points of individuals without a prior credit score and the loan amount sanctioned to them.'

'The dataset contains [40,000] unique records.' 

Columns relate to each loanee, their age, sex and location as well as their businesses, income and expenditure, domestic living arrangements, the purpose of the loan, the amount and length of the loan i.e., city, age, sex, 	social class,	primary business,	secondary business,	annual income,	monthly expenses, old dependents,	young dependents, 	home_ownership, 	type of house, 	occupants count, 	house area, sanitary availability,	water_availabity, loan purpose, 	loan tenure, 	loan installments, loan amount

## Collection process

- How was the data acquired? 
- If the data is a sample of a larger subset, what was the sampling strategy? 
- Over what time frame was the data collected?

Sources : Co-operative Credit Societies- set up with the aim of facilitating the complete credit needs for small and medium farmers.'

References : https://web.mit.edu/14.771/www/banerjee_09_23.pdf - Modeling Credit Markets - Abhijit Banerjee - Department of Economics, M.I.T

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)?

Noted 'Challenges:
The dataset is pretty raw and needs a lot of [Exploratory Data Analysis/Feature Engineering/Feature Selection
Some features have > 100 unique values'

## Uses

- What other tasks could the dataset be used for? 
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
- Are there tasks for which the dataset should not be used? If so, please provide a description.

According to the World Economic Forum '[a]ccess to credit poses a significant challenge for farmers worldwide, particularly for small and marginal farmers. This issue is even more severe in developing countries, where approximately 80% of smallholder farmers lack access to credit, as reported by the Food and Agriculture Organization. The implications of this credit gap are far-reaching, leading to lower productivity, limited adoption of new technologies, and reduced income for farmers.' 

The dataset should be used for the primary purpose of understanding how to assess credit worthiness in the absence of a credit history and the personal idnetifiable information should not be used for other purposes. This may create bias and breach the newly enacted India Digital Personal Data Protection (DPDP) Act, 2023, i.e, a cross-sectoral law on personal data protection.

Sources of potential bias could include :

•	Cognitive Bias or Implicit Bias, e.g., the creation of data or how data is weighted based on a person’s personal experiences and preferences which may 
  cause discrimination or prejudice toward a particular group or individual
•	Sampling Bias, Measurement Bias or Exclusion Bias, e.g., the data is inaccurate through inclusion of outliers, incorrect data, duplicate data and noise,  
  or is skewed with over or under-represented groups
•	Confirmation Bias, i.e., selecting information that is supportive of or confirms something known or believed and not data that would contradict such 
  beliefs
•	Overfitting or Temporal Bias, i.e., the algorithm / model is overfitted to the training data or the model is trained at a point in time but does not 
  predict accurate results at a future point in time. 
•	Algorithmic Bias, i.e., bias integrated into the algorithm that processes the data through, for example, programming errors, inaccurate weighting or 
  through the developers conscious or unconscious bias being integrated into the algorithm’s decision-making process

Such biases can result in harms to :
•	Individuals, e.g., in employment opportunities, housing, education, credit applications and privacy
•	Harms to Groups e.g., facial recognition, mass surveillance, civil rights
•	Societies, e.g., disinformation, safety
•	Companies and Institutions, e.g., reputational, economic, legal and regulatory

References
How geospatial datasets can improve lending to India's farmers - https://www.weforum.org/agenda/2023/07/how-geospatial-datasets-improve-lending-to-india-farmers/

## Distribution

- How has the dataset already been distributed? 
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?

https://www.kaggle.com/datasets/heydido/creditloan-dataset-rural-india
Creator : MIT 
License : https://www.mit.edu/~amini/LICENSE.md

## Maintenance

- Who maintains the dataset?

This specific dataset is indicated as not maintained

## Governance, Risk and Compliance concerns

1. The data has been preprocessed by the developer in a subjective manner. There is no formalised standard for outliers, missing values etc.
   Additional versions of the dataset exist 'cleaned' subjectively by other developers which may affect results and performance.
   e.g. https://www.kaggle.com/datasets/ikjotsingh221/rural-credit-dataset-cleaned

2. Personal Information is 'any information relating to an identified or identifiable natural person' (GDPR Article 4(1)). 
   The dataset contains personal information which has not been pseudonymised. Although names are not within the dataset specific information
   concerning age, city, dependents etc exists from which the identity of a natural person could be inferred.

   Mitigations : The dataset is from the 1950s / 1960s which limits risk as privacy law does not apply to those people who are deceased.
                 This, however, is specific to this dataset and would not apply to new datasets generated using current or recent information.

                 There may be an exception allowing use of the data under Schedule 2 Paragraph 27 (which provides an exemption if you are processing 
                 personal data for scientific or historical research purposes or statistical purposes) or Schedule 2 Paragraph 28 (which provides an 
                 exemption, if you are processing for archiving purposes in the public interest), although this would be in extremely limited circumstances.

3. Specific provisions within The India Digital Personal Data Protection Act 2023 (DPDPA) would need to be reviewed by legal.

4. The data is being used to process 
