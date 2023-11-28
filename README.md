##TECHNOHACKS-EDUTECH

#Task 3 : Diabetes Prediction

This repository contains code for building an Artificial Neural Network (ANN) model to predict diabetes in individuals. The code utilizes the Pima Indians Diabetes Database, available on Kaggle, and performs data preprocessing, handling of imbalanced data, and model training using TensorFlow/Keras.

Description
The code performs the following steps:

Data Preprocessing: The dataset is loaded using Pandas, and Z-score normalization (standardization) is applied to the input features.

Handling Imbalanced Data: The code uses Random Undersampling from the imbalanced-learn library to balance the dataset by reducing the size of the majority class.

Model Training: An ANN model is built using TensorFlow/Keras. The model architecture consists of two hidden layers with ReLU activation and an output layer with sigmoid activation. The model is trained using binary cross-entropy loss and the Adam optimizer. Optionally, class weights can be applied to address class imbalance during training.

Model Evaluation: The trained model is evaluated on the test set using accuracy, and a classification report is generated, including precision, recall, and F1-score for each class. Additionally, the model's accuracy and loss are plotted over the training epochs.

Results
The model achieves an accuracy of approximately 80% on the test set. The classification report shows precision, recall, and F1-score for both the positive and negative classes.


////////////////////////////////////////////////////////////////////////


# Task 4 : Image Classification






////////////////////////////////////////////////////////////////////////
# Task 6 : Fraud Transaction Detection
Using Neural Networks and Data Sampling for Fraud Transaction Detection
Fraud detection is a critical task for many industries dealing with online transactions. In this experiment, I used a dataset containing transaction data to build a model for detecting fraudulent transactions.

One challenge with this type of data is class imbalance, as the number of legitimate transactions far outweighs fraudulent ones. To address this, I tested two common sampling techniques - oversampling and undersampling.

With oversampling, I increased the number of fraudulent examples to match the legitimate ones. I then trained a neural network model over 50 epochs. This led to highly accurate results, with the model achieving 94% accuracy on the test set.

For undersampling, I reduced the number of legitimate transactions instead. While training accuracy improved over epochs, the best test accuracy was only around 70-75%.

In conclusion, oversampling proved more effective for this fraud detection problem by balancing the classes. The model was able to learn patterns to reliably distinguish between transaction types. These findings could help others addressing similar class imbalance issues.
/////////////////////////////////////////////////////////////////////////


