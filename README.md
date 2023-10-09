# NeuralNetworkTraining
# 1
Train NN over Covtype dataset.Define arbitrary achitecture of neural network. Pay attention to number of IN&amp;OUT neurons in the first and the last layer of neural network.
Use an adequate loss function. Train NN arbitrary number of epochs with arbitrary batch size. Find precision and recall over test dataset before and after training.
# 2
Define validation set. Implement early stopping during the trainig so training stops when loss over validation set start to rise. Tolerate 2 epochs of loss rise, after that stop training if loss rise in the third epoch as well.

# 3
Search space of hyperparameters. Vary at least 2 values of the initial training factors. In addition to the training factor, arbitrarily choose at least two other parameters
which affect the network architecture and vary the given parameters by at least 2 values. Choose a model which gives the best precision on the validation set.



# NOTE
# This solution has a flaw -> As accuracy is rising, precision is going down and I think that is due to imbalanced dataset. Oversampling or Undersampling should be done to fix this( I think so :) )
