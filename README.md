# Project Name
BeHealthy requires a **predictive model** which can **identify disease and treatment** from the patients interaction with doctor or ordering medicines online

## Table of Contents
Problem Statement

Technologies Used

Acknowledgements

Contacts

## Problem Statement

"BeHealthy" is a health-tech company and has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions. So, companies like "BeHealthy" are providing medical services, prescriptions and online consultations and generating huge data day by day.
The following snippet of medical data may be generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done. "The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy."
As we can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where one can understand the terms 'cancer' and 'chemotherapy'.

We have been given such a data set in which a lot of text is written related to the medical domain. There are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which we saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence. However, note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but we can build an algorithm to map the diseases and their respective treatment.
The train dataset is used to train the Continuous Random Field (CRF) model, and the test dataset is used to evaluate the built model.

Approach:
	1.	Data Preprocessing (EDA)
	2.	Observation of POS Tag and Repeated word frequencies for feature identification
	3.	Create feature function and extract feature from each sentence
	4.	Prepare input and Target variable for model
	5.	Build CRF model
	6.	Evaluate model using F1-score
	7.	Predict disease and treatment

## Technologies Used
Language - Python 3

Pandas - Dataframe, Content storage and processing

Regular Expression (re) - Identify the textual pattern

SpaCy - NLP, POS tag check

Warnings - To avoid warning messages

Sklearn_CRFsuite - Model building and Evaluation


## Acknowledgements
This project is part of a case study from Upgrad for building a NLP model used to identify and categorize various entities such as diseases, symptoms, drugs, procedures, and healthcare providers.


## Contact
Created by [@saswatdash]
