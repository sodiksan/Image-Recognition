Convolutional Neural Network (CNN) for Handwritten Digit Classification

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits using the mnist dataset. The primary focus of the project is to explore the impact of various hyperparameters on the accuracy of the CNN model. Specifically, we experiment with the number of filters, convolutional blocks, and learning rates to determine the optimal configuration for the highest classification accuracy.
Dataset
The mnist dataset contains images of handwritten numbers, and the goal is to classify each image into its corresponding digit using image classification techniques. Before feeding the images into the model, all images are resized to ensure uniform input dimensions.
Objectives
1.	Number of Filters: The first experiment evaluates the effect of varying the number of filters in each convolutional layer on the model's accuracy. By adjusting the number of filters across convolutional blocks, the goal is to identify the configuration that provides the best performance.

2.	Number of Convolutional Blocks:  In the second experiment, we tweak the number of convolutional blocks (i.e., the stack of convolution, activation, and pooling layers). We compare models with 2, 3, and 4 convolutional blocks, keeping all other parameters constant, to assess the impact of the number of blocks on accuracy.

3.	Learning Rate: In the third experiment, we examine the effect of varying the learning rate while keeping the number of filters, convolutional blocks, and other hyperparameters constant. The goal is to determine the optimal learning rate for achieving the best model accuracy.

Model Architectures
•	Filter Experimentation

Model 1: Three convolutional blocks with filters set to 32, 64, and 64.
Model 2: Three convolutional blocks with filters set to 64, 128, and 128.
Model 3: Three convolutional blocks with filters set to 32, 64, and 128.

After training each model, the accuracy of each configuration is recorded, and the optimal filter configuration is determined based on performance.

•	Convolutional Blocks Experimentation

Model 1: 2 convolutional blocks with a constant filter size.
Model 2: 3 convolutional blocks with the same filter size.
Model 3: 4 convolutional blocks with the same filter size.
The same filters, learning rate, activation function (ReLU), and other parameters are used across all implementations. The model accuracy is recorded, and inferences are drawn based on the effect of the number of blocks.

•	Learning Rate Experimentation

Model 1: Learning rate = 0.01.
Model 2: Learning rate = 0.02.
Model 3: Learning rate = 0.03.

For these experiments, the number of convolutional blocks, filters, activation functions, and other parameters remain constant. The accuracy for each learning rate is compared to determine the optimal rate.
Conclusion
The project thoroughly investigates the impact of key CNN hyperparameters on classification accuracy. By experimenting with different filter sizes, numbers of convolutional blocks, and learning rates, we provide insights into the optimal configuration for classifying handwritten digits using a CNN.
