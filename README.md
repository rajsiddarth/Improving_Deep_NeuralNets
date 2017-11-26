# Improving_Deep_NeuralNets
The framework is built upon assignments from Course 2: Improving Deep Neural nets in Coursera by Andrew Ng

https://www.coursera.org/learn/deep-neural-network



## Initialization
  
  Training the neural network requires specifying an initial value of the weights. A well chosen initialization method will help learning by

- Speeding up the convergence of gradient descent

- Increasing the odds of gradient descent converging to a lower training (and generalization) error

We will expriment with the following initialization methods :

- Zeros initialization -- setting initialization = "zeros" in the input argument.

- Random initialization -- setting initialization = "random" in the input argument. This initializes the weights to large random values.

- He initialization -- setting initialization = "he" in the input argument. This initializes the weights to random values scaled according to a paper by He et al., 2015.He Initialization" is similar to "Xavier initialization" except Xavier initialization uses a scaling factor for the weights W[l] of sqrt(1./layers_dims[l-1]) where He initialization would use sqrt(2./layers_dims[l-1]).)

## Regularization

We will experiment with the following approaches : 

- Non regularized approach

- L2 regularization

- Dropout

## Optimization

Implement various optimization techniques for faster and effiecient learning. Techniques implemented are

- Batch Gradient Descent

- Stochastic Gradient Descent

- Mini Batch Gradient descent

- Momentum

- Adam Optimization



