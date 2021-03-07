# bluepi
Repository for BluePi Assignment

# Data Preparation
There are columns with non-numeric values. In this case, I just imputed using zero because I don't want to create noise in images.
The training data are splitted into train set and validation set with sizing of validation set = 30%.

# Training
Convolutional Neural Network (CNN) is selected due to it is the most efficient for image data set.
For Intuition and operation behind CNN please refer to https://missinglink.ai/guides/convolutional-neural-networks/convolutional-neural-network-tutorial-basic-advanced/.

# Accuracy
The model's performance is measured by accuracy it can predict the validation set.
The training accuracy is 99.34% and validation accuracy is 98.72%.
To enhance the model performance we can adjust network architecture, add training data or training longer.

