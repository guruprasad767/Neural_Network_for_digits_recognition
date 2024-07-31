# Neural_Network_for_digits_recognition

This project implements a neural network from scratch to classify handwritten digits using the Keras MNIST dataset. The network consists of a single hidden layer with 10 neurons and uses a 28x28 input layer corresponding to the pixel dimensions of the images.

<b>Structure:</b> 1 layer with 10 neurons, each neurons has 784 weights and 1 bias.

<b>Activation Function:</b> The sigmoid activation function is used in the hidden layer to introduce non-linearity, which helps the network learn complex patterns in the data.

<b>Cost Function:</b> Cross-entropy loss is used as the cost function to measure the difference between the predicted probabilities and the actual labels. This function is well-suited for classification tasks where the output can be interpreted as probabilities.

<b>Gradient Descent:</b> The network is trained using batch gradient descent. Weights are initialized using Xavier initialization to ensure that the initial weights are neither too large nor too small, which helps in avoiding gradient vanishing or exploding issues.
