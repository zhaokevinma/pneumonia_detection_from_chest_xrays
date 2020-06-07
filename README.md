# Pneumonia Detection from Chest Xrays

*This repo is for personal use only.* 

## Project Overview
In this project, we will analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. We will be building upon the VGG 16 model, a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”. 

<a href="https://neurohive.io/en/popular-networks/vgg16/"><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fneurohive.io%2Fen%2Fpopular-networks%2Fvgg16%2F&psig=AOvVaw2pDaJ7bP40pmoRVxpvm_g7&ust=1591659928157000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMC2grvx8OkCFQAAAAAdAAAAABAD" title="VGG 16" alt="VGG 16"></a>

## Project Steps
This project has the following steps.
* Exploratory Data Analysis
* Building and Training Model
* Clinical Workflow Integration

## Note 
* The dataset is quite large (over 1GB) and is not uploaded to this GitHub repo. If you wish to run the notebook code blocks locally after cloning this repo, download the data from https://www.kaggle.com/nih-chest-xrays/data and put it in "./data/"
* The weights of our trained model in .hdf5 format is over 100 MB, the resctriction of size/file limitation on GitHub, and is therefore not uploaded. If you execute the 'Build and train model.ipynb' locally you will have the weights stored as './xray_class_my_model.best.hdf5' and be able to load it for inference
* Json file storing our model is not uploaded to this repo but it you execute all code blocks in 'Build and train model.ipynb' you should be able to get a file named 'my_model.json' in the same directory and use that in 'Inference.ipynb' to make predictions
