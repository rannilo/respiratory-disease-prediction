# What is this?

This codebase was to created to make it easier for machine learning researchers to create innovation in the medical field. Combining machine learning with the medical field would decrease false diagnoses and save lives.

This codebase is focused on predicting lung diseases from a breathing sounds dataset. 8 experiments were conducted on 5 different machine learning models. In addition, a novel data augmentation algorithm was performed and tested.

The following experiments were conducted on 4 classical machine learning methods (decision tree, random forest, SVM, XGBoost):

- Using all features to train the models
- Using less complex models to decrease overfitting
- Using class weights to counter dataset unbalancedness
- Using fewer features to decrease noise in the data

Experiments on the deep learning model (CNN) were as follows:

- Using all features to train the model
- Using class weights to counter dataset unbalancedness
- Using a novel data augmentation algorithm

# Instructions for use 

1. Clone the code from Github
2. Download data files and add them to the "dataframes" folder: https://drive.google.com/drive/folders/1ZEXr-3vSjL-_QR6x-cvRpm4XKJG3j-VU?usp=sharing
3. Run the "master" notebook to see the experiments process. Run the "data generation" notebooks to see the data extraction process.

# [Thesis](https://docdro.id/bATDzgO)

![Poster and high level overview of the code and model results](https://i.ibb.co/5xGTfbx/JPG-richard-annilo-poster-v2.jpg)
