# Neural-Network-Basic-Scratch

# Overview:

This repository contains an implementation of a Neural Network from scratch. A Neural Network is a powerful machine learning model inspired by the structure and function of the human brain. This implementation includes the internal workings of a basic Neural Network with three layers.

# Libraries Used:

1. numpy: For numerical computing and efficient array operations.
2. pandas: For data manipulation and analysis.
3. matplotlib.pyplot: For plotting graphs and charts.
4. math: For mathematical operations.
5. sklearn.metrics: For evaluating model performance metrics such as accuracy.
6. seaborn: For data visualization.
   
# Model Architecture:

The implemented Neural Network consists of three layers:

1. Input Layer: The input layer of the Neural Network corresponds to the features of the dataset.
2. Hidden Layer: The hidden layer contains two neurons, which perform computations on the input data.
3. Output Layer: The output layer contains one neuron, which produces the final prediction of the Neural Network.

# Functions Used:

1. Initialization: Functions are used to initialize the parameters of the Neural Network, including weights and biases.
2. Forward Propagation: Functions are implemented for forward propagation, which calculates the output of the Neural Network based on the input data and current parameters.
3. Activation Functions: Activation functions such as sigmoid or ReLU are used to introduce non-linearity into the Neural Network.
4. Loss Calculation: Functions are used to calculate the loss or error between the predicted output and the actual target values.
5. Backpropagation: Functions are implemented for backpropagation, which updates the parameters of the Neural Network based on the calculated gradients of the loss function.
6. Training: Functions are used to train the Neural Network by iteratively updating the parameters using forward propagation and backpropagation.
   
# Performance Metrics:

1. Classification Report: The classification report provides a summary of various metrics such as precision, recall, and F1-score for each class.
2. Confusion Matrix: The confusion matrix shows the number of true positives, true negatives, false positives, and false negatives, which helps in understanding the model's performance.
3. Accuracy Score: The accuracy score measures the proportion of correctly classified instances out of the total instances.
Usage:
4. Clone this repository to your local machine.
5. Install the required dependencies listed in the requirements.txt file.
6. Prepare your dataset and ensure it is in the appropriate format for classification.
7. Modify the code as needed to fit your dataset and problem.
8. Run the appropriate script to train and evaluate the Neural Network.
9. Analyze the performance metrics and adjust the model parameters as necessary for better results.
