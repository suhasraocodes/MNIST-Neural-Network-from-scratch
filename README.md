# MNIST Neural Network from Scratch

This project implements a neural network from scratch to classify handwritten digits from the MNIST dataset, achieving an accuracy of 85%. The implementation is based on the video tutorial by [Samson Zhang](https://www.youtube.com/watch?v=w8yWXqWQYmU).

## Network Architecture

- **Input Layer**: 784 units (28x28 pixels)
- **Hidden Layer**: 10 units with ReLU activation
- **Output Layer**: 10 units with softmax activation

## Code Description

### Data Preparation
The dataset is shuffled and split into training and development sets, with pixel values normalized.

### Initialization of Parameters
Weights and biases are initialized randomly.

### Activation Functions
ReLU and softmax functions are used for activations.

### Forward and Backward Propagation
Forward propagation computes the activations, while backward propagation computes the gradients for parameter updates.

## Usage

1. Prepare and preprocess the MNIST dataset.
2. Initialize parameters using `init_params()`.
3. Implement forward propagation with `forward_prop()`.
4. Use backward propagation with `backward_prop()` to update the parameters.
5. Train the model and evaluate its performance.

## References

- [Samson Zhang: Neural Network from Scratch](https://www.youtube.com/watch?v=w8yWXqWQYmU)
