# Image-Classification-using-Feed-Forward-Neural-Network

This project comprises two phases: Phase 1 involves implementing a feed-forward neural network **from scratch**, while Phase 2 focuses on implementing the same using `Keras` and `TensorFlow` packages. Each phase addresses unique datasets and objectives.

## Phase 1
In this phase, we implement a feed-forward neural network from scratch by using `Numpy` library to categorize images of `CIFAR-10` dataset. Each image is first flattened as a vector and then is given as the network input. Each element of this vector (equivalent to one image pixel) is a feature. Based on these features and by making nonlinear combinations, the network is supposed to adjust the weight of the connections between its layers so that its output, with the least error, correctly predicts the corresponding input image class.
### Objectives
- Data visualization and preprocessing, including min-max normalization and one-hot encoding of labels
- Implementation of `Identical`, `Relu`, `LeakyRelu`, `Sigmoid`, `Softmax`, and `Tanh` activation functions
- Implementation of `CrossEntropy` loss function
- Implementation of `Layer` and `FeedForwardNN`
- Test data classification and evaluate the impacts of network weighting methods, learning rate, activation function, and batch size


## Phase 2
This phase aims to get more familiar with `Keras` and `TensorFlow` libraries to build a neural network model for predicting the type of animal in a given image using the `Oregon Wildlife` dataset, including four categories, namely `elk`, `raven`, `bald_eagle` and `raccoon`.
### Objectives
- Preprocessing, including grayscaling the images and one-hot encoding of labels
- Neural network implementation
- Data classification and evaluation of the impacts of optimizer, number of epochs, loss function, and regularization
- Dimensionality reduction for data visualization