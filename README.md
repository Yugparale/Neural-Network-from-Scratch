# Neural-Network-from-Scratch
lightweight, modular Neural Network  implementation built from the ground up using NumPy

- Modular Architecture: Easily add or remove layers using a Sequential-style API.Activation Functions: Includes implementations for Tanh and Sigmoid.
- Loss Functions: Supports Mean Squared Error (MSE) for regression/simple logic and Binary Cross-Entropy (BCE) for classification tasks.
- Flexible Layers: Fully connected (Dense) layers with automated weight initialization.
- Custom Training Loop: Supports stochastic gradient descent with adjustable learning rates and epochs.

Implementation Details
- This library follows a standard object-oriented approach to deep learning
- Dense Layer: Implements $Z = XW + b$ and computes gradients for both weights and biases   during backpropagation.
- Activations: Each activation class manages its own forward pass and derivative calculation.
- NeuralNetwork Class: Acts as the orchestrator, managing the flow of data through the layers and handling the training process.
