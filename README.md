# TECHNOHACKS-EDUTECH


Using Neural Networks and Data Sampling for Fraud Transaction Detection
Fraud detection is a critical task for many industries dealing with online transactions. In this experiment, I used a dataset containing transaction data to build a model for detecting fraudulent transactions.

One challenge with this type of data is class imbalance, as the number of legitimate transactions far outweighs fraudulent ones. To address this, I tested two common sampling techniques - oversampling and undersampling.

With oversampling, I increased the number of fraudulent examples to match the legitimate ones. I then trained a neural network model over 50 epochs. This led to highly accurate results, with the model achieving 94% accuracy on the test set.

For undersampling, I reduced the number of legitimate transactions instead. While training accuracy improved over epochs, the best test accuracy was only around 70-75%.

In conclusion, oversampling proved more effective for this fraud detection problem by balancing the classes. The model was able to learn patterns to reliably distinguish between transaction types. These findings could help others addressing similar class imbalance issues.
