This project implements a **Multilayer Perceptron (MLP) neural network** to classify handwritten digits using the **MNIST dataset**, which contains grayscale images of digits from 0 to 9. The data is preprocessed by normalizing pixel values to a range of 0 to 1 and converting the labels into one-hot encoded vectors for better compatibility with the neural network.

The MLP model consists of a flattening layer to convert the 28x28 pixel images into a 1D vector, followed by two dense layers with 512 and 256 neurons respectively, both using the ReLU activation function. The final output layer applies a softmax function to classify the images into one of 10 classes, representing the digits.

The model is trained over 10 epochs with a batch size of 32, and the performance is evaluated using a validation split. After training, the model's predictions are tested by selecting 50 random images from the test set. These images are then plotted alongside their true and predicted labels, providing a visual comparison of the model's performance.

This approach effectively demonstrates how an MLP model can be applied to the MNIST dataset for handwritten digit recognition, showcasing the model's predictive capabilities.
