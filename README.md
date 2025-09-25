# Interpretable Machine Learning Framework for Predicting the Reactivity of Trifluoromethylating Reagents

💡 This repository contains the following files.

 - data_raw.csv - 1826 2d and 3d descriptors, Smiles, TC+DA values

 - data.csv - 249 descriptors, Smiles, TC+DA values, Reagent ID and TOR (type of reagent)

 - predictions_train_nn.xlsx - Train set predictions on the NN model (tuned) trained on 5 descriptors

 - predictions_val_nn.xlsx - Validation set predictions on the NN model (tuned) trained on 5 descriptors

 - predictions_test_nn.xlsx - Test predictions on the NN model (tuned) trained on 5 descriptors

 - train_ids - Pickel file containing train indices

 - val_ids - Pickel file containing val indices

 - test_ids - Pickel file containing test indices

 - preprocessing.ipynb - Python code for preprocessing.

 - model.ipynb - Python code for model development (with default hyperparameters)

 - hyper_p_tuning.ipynb - Hyperparameter tuning for NN

 - nn.keras - Saved NN model with untuned parameters

 - nn_tuned.keras - Saved NN model with tuned parameters






