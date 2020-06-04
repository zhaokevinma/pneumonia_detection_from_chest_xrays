# pneumonia_detection_from_chest_xrays

*This repo is for personal use only.* 

## Project Overview
In this project, we will analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. 

## Project Steps
This project has the following steps.
* Exploratory Data Analysis
* Building and Training Your Model
* Clinical Workflow Integration
* FDA Preparation

## Note 
* The dataset is quite large (over 1GB) and is not uploaded to this GitHub repo. If you wish to run the notebook code blocks locally after cloning this repo, download the data from https://www.kaggle.com/nih-chest-xrays/data and put it in "./data/".
* The weights of our trained model in .hdf5 format is over 100 MB and is over the resctriction of size/file limitation on GitHub, and is therefore not uploaded. If you execute the 'build_and_train_model.ipynb' locally you will have the weights stored as './xray_class_my_model.best.hdf5'
* Model json is not uploaded to this repo but it you execute all code blocks in 'Build_and_train_model.ipynb' you should be able to get one in the same directory and use that in 'Inference.ipynb'
