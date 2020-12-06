# Convolutional_NN

A simple single layer Convolutional NN, using Pooling and Convolutional Layer. Additionally adding zero padding to keep the image size the same. Furthermore, Masking is also used. Forward propagation and Backward propagation has been implimented successfully. 

# Application

Uses TensorFlow to ease the application of NN and apply successfully to the Sign data set. This achieves a train accuracy of 94% with 10 epochs and a Test accuracy of 78%.
This model shows high bias as the Human Level Performance is expected to be 0.03% and the difference from Bayes Error is big. This can be improved by increasing the number of neurons and layers in the NN, making it deeper. Increasing the number of epochs can also decrease thee high bias.
This model also shows high variance as the test accuracy has a big difference from the train accuracy. This can solved by implimenting Cross validation data set with split of 60 20 20 if data set is small and 98 1 1 if data set is high. Regularization can also be added to reduce variance.
