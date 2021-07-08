# Absenteeism at Work project:

This code consists of an exploratory data analysis and the validation of Random Forest Classifier Model, using SMOTE for unbalanced data.

**Question to be answered:** Can you build a machine learning model to accurately predict whether or not the workers in the dataset have absence of work?  

## About the data and context:

The database was created with records of absenteeism at work from July 2007 to July 2010 at a courier company in Brazil.

Number of Instances: 740
Number of Attributes: 21
Missing Values: 0

## Reasons for absence:

ICD-10 Codes: https://icd.who.int/browse10/2016/en

- I Certain infectious and parasitic diseases
- II Neoplasms
- III Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism
- IV Endocrine, nutritional and metabolic diseases
- V Mental and behavioural disorders
- VI Diseases of the nervous system
- VII Diseases of the eye and adnexa
- VIII Diseases of the ear and mastoid process
- IX Diseases of the circulatory system
- X Diseases of the respiratory system
- XI Diseases of the digestive system
- XII Diseases of the skin and subcutaneous tissue
- XIII Diseases of the musculoskeletal system and connective tissue
- XIV Diseases of the genitourinary system
- XV Pregnancy, childbirth and the puerperium
- XVI Certain conditions originating in the perinatal period
- XVII Congenital malformations, deformations and chromosomal abnormalities
- XVIII Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified
- XIX Injury, poisoning and certain other consequences of external causes
- XX External causes of morbidity and mortality
- XXI Factors influencing health status and contact with health services.

And 7 categories without ICD:

- 22 patient follow-up
- 23 medical consultation
- 24 blood donation
- 25 laboratory examination
- 26 unjustified absence
- 27 physiotherapy
- 28 dental consultation

## About the project:

This project works on many important points in data science, such as decision making, which features are important for the model?

Or teach us how to deal with unbalanced data.

## How to use:

Download the attached files and run on jupyter notebook in your machine.

Dataset link [Kaggle](https://www.kaggle.com/kewagbln/absenteeism-at-work-uci-ml-repositiory) 
