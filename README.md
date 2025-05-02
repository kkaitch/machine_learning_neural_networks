## Project Goal
This project is to train neural network models for image classification.

## Introduction
In this project, the task is to train models that correctly predict where the vehicle in a given image is a truck or a car / automobile.

The project includes:

* Neural networks fine-tuning
* Convolutional Neural Network (CNN)
* Feature maps

## Dataset
A set of given vehicle images.

## Key Findings
* Neural networks achieved high classification accuracy
The trained neural network model achieved strong classification performance on the vehicle dataset, indicating that neural networks are well-suited for distinguishing between different vehicle types based on the input features.

* Tuning model improved results
Experimenting with different numbers of hidden layers and neurons helped improve accuracy. A moderate-depth network (e.g., 1–2 hidden layers) struck a balance between learning complex patterns and avoiding overfitting.

* Normalization increased performance
Applying feature scaling (e.g., MinMax or StandardScaler) significantly improved training convergence and final model accuracy, highlighting the importance of preprocessing in neural network workflows.

* Validation accuracy was consistent with training accuracy
The gap between training and validation accuracy was small, suggesting that the model generalized well and did not overfit to the training data.

* Some class confusion rRemained
The confusion matrix revealed that while most classes were predicted accurately, there was minor confusion between similar vehicle types, indicating room for improvement—potentially through more complex architectures or additional features.
