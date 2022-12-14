# Project: Pneumonia Detection from Chest X-Rays

## Introduction
In this project, you will apply the skills that you have acquired in this 2D medical imaging course to analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, you will formally describe your model, the data that it was trained on, and a validation plan that meets FDA criteria.

You will be provided with the medical images with clinical labels for each image that were extracted from their accompanying radiology reports.

The project will include access to a GPU for fast training of deep learning architecture, as well as access to 112,000 chest x-rays with disease labels acquired from 30,000 patients.

## Project Highlight
This project is designed to give you hands-on experience with 2D medical imaging data analysis and preparation of a medical imaging model for regulatory approval.

Upon completion of this project, you would be able to:

recommend appropriate imaging modalities for common clinical applications of 2D medical imaging
perform exploratory data analysis (EDA) on medical imaging data to inform model training and explain model performance
establish the appropriate ‘ground truth’ methodologies for training algorithms to label medical images
extract images from a DICOM dataset
train common CNN architectures to classify 2D medical images
translate outputs of medical imaging models for use by a clinician
plan necessary validations to prepare a medical imaging model for regulatory approval

## Project Steps
This project has the following steps.

- Exploratory Data Analysis
- Building and Training Your Model
- Clinical Workflow Integration
- FDA Preparation

## Dataset
You can download the data from the [kaggle website](https://www.kaggle.com/datasets/nih-chest-xrays/data) and run it locally

## Files

This project contains:

- EDA.ipynb: This is the file I did perform the EDA.
- Build and train model.ipynb: This is the file I did build and train the DL model.
- Inference.ipynb: This is the file you I did perform clinical workflow integration.
- *.dcm files: They are the test files to test the clinical workflow integration.
- sample_labels.csv: This is the file that should be used to assess images in the pixel-level.
- FDA_Submission_Template.md: This is the template that I did perform the FDA submission. 

