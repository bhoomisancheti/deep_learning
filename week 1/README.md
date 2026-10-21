# Week 01 - Neural Network Implementation for XOR

## Program Title
**XOR Logic Gate Implementation Using Neural Networks**

## Aim
To build a neural network that performs the XOR logical operation using two approaches: a manual implementation with NumPy and a Keras-based model. The results of both implementations are compared.

## Dataset
The XOR truth table is used to train and test the neural networks.

| Input 1 | Input 2 | Output |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## Program 1(a): Neural Network Using NumPy
A neural network is developed from scratch using NumPy without relying on a deep learning framework. The implementation covers the following concepts:

- Sigmoid activation function and its derivative
- Forward propagation to calculate the network output
- Error calculation to measure prediction differences
- Backpropagation to adjust the network parameters
- Updating weights and biases during training
- Training the network for 10,000 epochs

## Program 1(b): Neural Network Using Keras
The XOR problem is also solved using TensorFlow's Keras API. The model contains the following components:

- Input: 2 features
- Hidden layer: 8 neurons with ReLU activation
- Output layer: 1 neuron with sigmoid activation
- Loss function: Binary cross-entropy
- Optimizer: Stochastic Gradient Descent (SGD)
- Learning rate: 0.1
- Training duration: 1,000 epochs

## Results
Both implementations successfully learn the XOR logic and generate predictions matching the expected output pattern:

```text
0
1
1
0
```

The NumPy implementation demonstrates the working of neural network training algorithms, while the Keras implementation provides a simpler way to build, train, and evaluate a neural network. The Keras model achieved 100% accuracy on the four XOR input examples.

## Repository Structure

```text
Week-01-XOR/
├── Program-1A-XOR-Neural-Network.py
├── Program-1B-Keras-XOR.py
├── screenshots/
│   └── program output screenshots
└── README.md
```

## Conclusion
The XOR logical operation was implemented using both a manually constructed neural network and a Keras model. This exercise helps understand the basic principles of neural networks, including forward propagation, backpropagation, activation functions, and model training.
