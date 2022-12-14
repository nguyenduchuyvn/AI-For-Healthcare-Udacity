# Project: Patient Selection for Diabetes Drug Testing

## Context
EHR data is becoming a key source of real-world evidence (RWE) for the pharmaceutical industry and regulators to make decisions on clinical trials. You are a data scientist for an exciting unicorn healthcare startup that has created a groundbreaking diabetes drug that is ready for clinical trial testing. It is a very unique and sensitive drug that requires administering the drug over at least 5-7 days of time in the hospital(X number of days based off of distribution that I will see in data and cutoff point) with frequent monitoring/testing and patient medication adherence training with a mobile application. You have been provided a patient dataset from a client partner and are tasked with building a predictive model that can identify which type of patients the company should focus their efforts testing this drug on. Target patients are people that are likely to be in the hospital for this duration of time and will not incur significant additional costs for administering this drug to the patient and monitoring.

In order to achieve your goal you must first build a regression model that can predict the estimated hospitalization time for a patient and also provide an uncertainty estimate range for that prediction so that you can rank the predictions based off of the uncertainty range.

## Expected Hospitalization Time Regression Model
Expected Hospitalization Time Regression and Uncertainty Estimation Model: Utilizing a synthetic dataset(upsampled, denormalized, with line level augmentation) built off of the UCI Diabetes readmission dataset, students will build a regression model that predicts the expected days of hospitalization time and an uncertainty range estimation.

This project will demonstrate the importance of building the right data representation at the encounter level, with appropriate filtering and preprocessing/feature engineering of key medical code sets. This project will also require students to analyze and interpret their model for biases across key demographic groups. Lastly, students will utilize the TF probability library to provide uncertainty range estimates in the regression output predictions to prioritize and triage prediction uncertainty levels.

In the end you will be creating a demographic bias analysis to detect if your model has any bias which we know can be a huge issue in working with healthcare data!


## Dataset
Due to healthcare PHI regulations (HIPAA, HITECH), there are limited number of publicly available datasets and some datasets require training and approval. So, for the purpose of this exercise, we are using a dataset from UC Irvine that has been modified for this course. Please note that it is limited in its representation of some key features such as diagnosis codes which are usually an unordered list in 835s/837s (the HL7 standard interchange formats used for claims and remits).

https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008 Data Schema The dataset reference information can be https://github.com/udacity/nd320-c1-emr-data-starter/tree/master/project/data_schema_references. There are two CSVs that provide more details on the fields and some of the mapped values.

## Environment Setup
For step by step instructions on creating your environment, please go to https://github.com/udacity/cd0372-Applying-AI-to-EHR-Data

