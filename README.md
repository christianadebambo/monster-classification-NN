# Monster Classification with Neural Network

This repository contains a solution for the "Monster Classification" problem using a feedforward neural network with regularization. The goal is to predict the type of monsters (ghouls, goblins, or ghosts) based on their characteristics.

Dataset taken from [Kaggle](https://www.kaggle.com/competitions/ghouls-goblins-and-ghosts-boo/overview)

## Code Overview

The code is written in Python and utilizes the following libraries:

- **numpy:** For numerical computations and array manipulation
- **pandas:** For data manipulation and analysis
- **scipy:** For scientific computing and optimization

Here's a summary of the major steps in the code:

- **Data Loading:** The training and test datasets are loaded from CSV files.
- **Feature Engineering:** Additional features are created by multiplying different combinations of existing features to capture possible interactions and improve the model's performance.
- **Data Preparation:** The data is transformed into input feature matrices and target variable matrices suitable for training the neural network.
- **Neural Network Architecture:** The size of the hidden layer and the learning rate are set. The parameters for the neural network are initialized with random values.
- **Forward Propagation:** The input features are propagated through the network to calculate the predicted outputs.
- **Back Propagation:** The error between the predicted outputs and the actual targets is propagated backward through the network to update the parameters.
- **Cost Function:** The cost function is defined to calculate the loss between the predicted outputs and the actual targets, including regularization terms to prevent overfitting.
- **Model Training:** The cost function is minimized using the TNC optimization method, and the optimized parameters are obtained.
- **Prediction:** The optimized parameters are used to make predictions on the training and test datasets.
- **Evaluation:** The accuracy of the predictions on the training dataset is calculated and displayed.
- **Submission:** The predictions on the test dataset are saved in a CSV file for submission.

## Usage

To use this code, follow these steps:

- Ensure that Python is installed on your system along with the required libraries mentioned in the code.
- Download the training and test datasets from the provided source and place them in the appropriate directory.
- Adjust the file paths in the code to match the location of the dataset files.
- Execute the code to preprocess the data, train the neural network, and make predictions
- Evaluate the accuracy of the predictions on the training dataset.

Please note that this code serves as a baseline solution and may require further customization, optimization, or experimentation to achieve better results.
