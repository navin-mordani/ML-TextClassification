# Linear and Non-Linear Classification of Text by Subject

Project 3 for Comp 551, Fall 16 at McGill University

Kaggle Team : Poco a Poco


## Introduction

The project evaluates the performance of linear and nonlinear classifiers in the categorization of abstracts from technical papers.
The dataset used is of 88639 abstracts, each classified as coming from one of 4 different subjects: mathematics, computer science, physics, and
statistics. 

## Data Preprocessing 

[feature_extraction_code.ipynb](code/Feature_Extraction/feature_extraction_code.ipynb) showcases data preprocessing which includes stemming, stop word removal, vectorization.

## Models

### SVM 
The ipython notebooks for different implementations of SVM along with the feature selection methods can be found in the [code/SVM](code/SVM/) folder.

### Naive Bayes
The code for multinomial as well as bernouilli naive Bayes can be found in [code/NaiveBayes](code/NaiveBayes/)

###KNN
The code for KNN is present in [code/KNN/](code/KNN/)

## Details

First execute the feature_extraction post which each of the classifiers can be run. Some of the files have been coded in ipython notebook
and a few in the traditional python format. This project was part of a Kaggle Competition.

## Authors

Charles C Onu, McGillID : 260663256, EmailId : charles.onu@mail.mcgill.ca

Navin Mordani, McGillID : 260744902, EmailId : navin.mordani@mail.mcgill.ca

Ramchalam K R, McGillID : 260711189, EmailId : ramchalam.kinattinkararamakrishn@mail.mcgill.ca


