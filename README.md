# COMP3000-Project
Version Control Repository for My COMP 3000 Project.

This project covered the development of a Machine Learning powered Network Intrusion Detection System (NIDS), it was developled using Python 3 as the development language and Jupyter Notebook as the IDE.

This repository contains the three Jupyter Notebook files that were developed over the course of this project, the dissertation that was written over the course of the project detailing the research into AI IDS systems, the planning of the system, and the implementation of it. It also contains the three code files that were developed over the course of the project, the first of these being ModelAccuracyTest which covers the accuracy testing of 5 machine learning algorithms, these algorithms are RandomForest, XGBoost, Logistic Regression, LinearSVM, and KNN. The Random Forest model achieved the highest results with an accuracy of 0.9099.

The second code file takings the preprocessing and training of the Random Forest model and then dumps the feature columns and model data to two files allowing for reuse of the model without the need for retraining. The third file contains code to load the trained model, and run predictions againsts the UNSW NB-15 testing dataset, outputting the results to a TXT file, and if suspicious activity is detected, it will send out an email alert to pre-decided email address.

This repo also contains the Random Forest model and feature column files that were created by the second code file. All code files require the UNSW NB-15 Testing and Training datasets to work these can be downloaded from the link below.

https://research.unsw.edu.au/projects/unsw-nb15-dataset

This project made use of several python libaries that made development possible can be found below

* Scikit-Learn

* Pandas

* Numpy

* XGBoost

* Joblib

* SMTPLib

These libraries are critical to the function of this project, and if are not installed, the code will not work.

If you are attempting to use this code on a different device, the file paths MUST be changed to suit the new device as these paths are tailored to the device development took place on.
