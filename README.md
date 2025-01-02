# Handwritten-Digit-Recognition
This project implements a neural network for recognizing handwritten digits from the MNIST dataset, which consists of 28x28 pixel grayscale images of digits 0-9. The network is designed with an input layer of 784 neurons (one for each pixel), a hidden layer with 128 neurons using ReLU activation, and an output layer of 10 neurons representing the digit classes 0-9. The model is trained using mini-batch gradient descent with a learning rate of 0.01, and the cross-entropy loss function is employed to measure the difference between predicted and actual labels. The network's weights are initialized using Xavier initialization, and the training process runs for 50 epochs to ensure the model learns the complex patterns in the data.

The goal of the project is to achieve high accuracy in classifying handwritten digits, typically around 96% on the test set. The model's performance is evaluated using accuracy score metrics, and its success demonstrates the power of deep learning techniques such as backpropagation and stochastic gradient descent for image classification tasks. By leveraging fundamental neural network principles like ReLU activation, softmax output, and one-hot encoding, this project provides an effective introduction to building and training neural networks for computer vision tasks.






