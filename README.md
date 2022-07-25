# Plant-DTI

This repository provided train, test data, and python codes in jupyter notebook for constructing Plant-DTI model and optimize the hyperparameter of the model.

Users can download this repository to run all codes provided.

To predict the DBD-TFBS interactions, the Plant-DTI is implemented as a web application tool and freely available at https://bml.kmutt.ac.th/Plant-DTI.

## Prerequisite install
To run this code requires:

- python >= 3.6 
- pandas module 
- numpy module
- matplotlib module
- scikit-learn module VERSION 0.23.2
- pickle module
- textwrap module

## Data
This folder contains train and test data of Plant-DTI which used as input for constructing Plant-DTI model or optimize the hyperparameter of the model.

## OUTPUT
Constructed model and hyperparameter optimiztion results will be generated in this folder. 

## train.ipynb
This code is for training the model which Plant-DTI used random forest classifier with number of trees is 100.

We use Random within model length 7 as an example to show the model training process. For other model, Please change the input data to before training.

The output is the constructed model which will be generated in OUTPUT folder.

## hyperparameter_tunning.ipynb
This code is for optimizing the hyperparameter of the model which Plant-DTI used random forest classifier and vary number of trees from 1 to 150 trees. The optimized hyperparameter will be selected based on F1-score.

We use Random within model length 7 as an example to show the model optimizing process. For other model, Please change the input data to before training.

The output is the hyperparameter optimiztion results which will be generated in OUTPUT folder.
