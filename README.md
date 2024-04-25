- 👋 Hi, I’m Mohammed (SILVA)
- 👀 I’m interested in ROBOTICS / AI
- 📫email : silvapi1994@gmail.com

# SilvaNet

SilvaNet is a simple neural network library implemented in Python for educational purposes. It provides a framework for building and training various types of neural network architectures, including fully connected networks recurrent neural networks (RNNs), and more.

## Features

- Implementation of various neural network layers:
  - Fully connected (Dense) layers
  - Flatten layer
  - Embedding layer
  - RNN cell (RNNCell)
  - Dropout layer
- Support for popular activation functions:
  - ReLU
  - Sigmoid
  - Tanh
- Implementation of loss functions:
  - Softmax Cross-Entropy
- Optimization algorithms:
  - Stochastic Gradient Descent (SGD)
  - Adam
  - RMSprop
  - Adagrad
- Save and load trained models
- Evaluation of trained models
- Prediction using trained models
- Model summary functionality




import numpy as np
from autograd import Tensor
from nn.Layers import Sequential, Dense, Conv2D, MaxPool2D, Flatten, Embedding, RNNCell, Dropout
from nn.activations import ReLU, Sigmoid, Tanh
from nn.losses import SoftmaxCrossEntropy
from nn.optimizers import SGD

# Define a simple neural network architecture
model = Sequential([
    Linear(784, 128),
    ReLU(),
    Linear(128, 10),
    ........
    Flatten(),
    Dense(32*7*7, 128, activation='relu'),
    Dense(128, 64, activation='relu'),
    RNNCell(n_inputs=64, n_hidden=64, n_output=10, activation='tanh'),
    Dropout(drop_prob=0.5),
    Embedding(vocab_size=1000, dim=100),
    Dense(100, 10)  # Assuming 100 is the output dimension of the embedding layer
])

# Create a neural network object with specified loss function and optimizer
neural_network = NeuralNetwork(model, SoftmaxCrossEntropy(), SGD(learning_rate=0.01))

# Load your training and testing data (assuming you have them loaded as X_train, y_train, X_test, y_test)

# Train the neural network
neural_network.fit(X_train, y_train, epochs=10, batch_size=64)

# Evaluate the trained model
neural_network.evaluate(X_test, y_test)

# Predict using the trained model
predictions = neural_network.predict(X_test)

# Save the trained model
neural_network.save_model("trained_model.pkl")

# Load the trained model
loaded_model = NeuralNetwork.load_model("trained_model.pkl")

# Evaluate the loaded model
loaded_model.evaluate(X_test, y_test)
