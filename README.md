![MNIST Handwritten Digit Recognition using ANN](https://github.com/mmuzammil196/MNIST-Handwritten-Digit-Recognition-using-ANN/assets/77389040/c0c5ba70-79b1-4c33-9783-9c2ca60333eb)


This project is an implementation of an Artificial Neural Network (ANN) algorithm for recognizing hand-written digits from the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

The main goal of this project is to train an ANN model on the training dataset and achieve a high accuracy in predicting the correct digit label for the test images. The model successfully achieves an accuracy of 97% on the test set, demonstrating its effectiveness in recognizing handwritten digits.

The notebook includes the following key steps:

Data preprocessing: The MNIST dataset is loaded and preprocessed by scaling the pixel values to a range of 0-1 and converting the labels to categorical format.
Model building: An ANN model is constructed with multiple hidden layers using the Keras library. The model architecture is defined, and appropriate activation functions and optimizer are selected.
Model training: The model is trained on the preprocessed training dataset. The training process involves forward propagation, backpropagation, and weight optimization to minimize the loss function.
Model evaluation: The trained model is evaluated on the test dataset to measure its accuracy in digit recognition.
Data visualization: The notebook includes visualizations of sample images from the MNIST dataset, showcasing the diversity and complexity of handwritten digits.
