# Plant-DTI
Python jupyter notebook for constructing Plant-DTI model and optimize the hyperparameter of the model.

The Plant-DTI is implemented as a web application tool and freely available at https://bml.kmutt.ac.th/Plant-DTI.

## Prerequisite install
To run this code requires:

- python 3.6
- pandas module
- numpy module
- matplotlib module
- scikit-learn module
- pickle module
- textwrap module

## Data
This folder contains train and test data of Plant-DTI which used as input for constructing Plant-DTI model or optimize the hyperparameter of the model.

## OUTPUT
Constructed model and hyperparameter optimiztion results will be generated in this folder. 

### model_construction.ipynb
This code is for model construction which Plant-DTI used random forest classifier with number of trees is 100.

We use Random within model length 7 as an example to show the model training process. For other model, Please change the input data to before training.

The output is the constructed model that will be generated in OUTPUT folder.
