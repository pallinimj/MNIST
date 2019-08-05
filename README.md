# MNIST
Comparison of techniques for predicting MNIST images.  This is based on the datasets available in the Kaggle competition (https://www.kaggle.com/c/digit-recognizer) on this data.  

One set of models takes a classification approach.  I compare the results of a random forest, a PCA with random forest, and a PCA with random forest using scaled data.  The random forest produced the best prediction on Kaggle, 94.4%.

The other approach built a neural network with varying layers and nodes to increase accuracy.  The best of these models produced was 96.8% accurate on the training data and 94.7% accurate on the test data submitted to Kaggle.  
