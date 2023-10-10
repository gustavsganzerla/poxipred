poxipred_v1.ipynb - this file contains the Python notebook that trains the three models implemented by PoxiPred. The user needs the training data in order to execute this.

model_antigen.zip - this is the saved Keras model that was trained with antigens and non-antigens. 

model_epitope.zip - this is the saved keras model that was trained with epitopes and non-epitopes.

model_epitope_type.model - this is the XGBoost model that classified the true epitopes as per their t-cell reactivity (i.e., cd4+ and cd8+).

All the .csv files contain the individual predictions for each out of the 25 poxviruses in which antigens, t-cell epitopes, and t-cell epitope reactivity were predicted for.
