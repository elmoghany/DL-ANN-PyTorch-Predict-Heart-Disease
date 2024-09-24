# Objective
For the UCI dataset of heard disease, we want to predict if the patient has a heart disease or not
We want to predict the accuracy of the ANN model in predicting if any patients has a heart disease or not

# Illustration
1) Training: We train a linear ANN model on the dataset
2) Input features: 13 feature
3) Output Target: Binary True "Has heart disease" or False 

# Model & Architecture
1) ANN DL Model
2) input layer:   13 -> relu -> 64 
3) Hidden Layer1: 64 -> relu -> 2
4) Hidden Layer2: 2  -> relu -> 2
5) Output Layer:  2  -> 1
6) Normalize inputs using z-transform
8) Use of BCEWithLogitsLoss "which is with sigmoid" because we do a binary prediction 0 or 1


# Results
1) Accuracy: Got 82% accuracy for the prediction of the heart disease using the test dataset but the training model overfitted to 100%

# Conclusions:
1) The dataset is 300 rows which is very low. We need a larger dataset to get better accuracy
