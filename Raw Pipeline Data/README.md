### This folder contains the raw outputs from the machine learning pipelines.
Each file is the raw output from the machine learning pipelines in .csv format

The 'RS10' and 'RS20' files are from the 10 and 20 RandomizedSearchCV iteration pipelines respectively. Both were set to refit for the highest Matthews correlation coefficient (MCC). The "parameters_used" column contains the final hyperparameters chosen by RandomizedSearchCV to train the classifier on.

The 'no_params' file is from the pipeline in which no RandomizedSearchCV was used, and no hyperparameter tuning was done, therefore using the default hyperparameters defined within the [Scikit-learn version 1.2.1](https://scikit-learn.org/stable/whats_new/v1.2.html#version-1-2-1). 


