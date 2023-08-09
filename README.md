# Concrete Strength Prediction Analysis

In this analysis, we explore the prediction of concrete strength using neural networks. We cover the following parts:

## Part A: Baseline Model

In this part, we build a baseline neural network model with one hidden layer and evaluate its performance.

### Part A Steps:
- Load the dataset from `concrete_data.csv`.
- Split the data into features (X) and target (y).
- Split the data into training and test sets.
- Build and train the baseline neural network model.
- Predict using the trained model.
- Calculate the Mean Squared Error (MSE) and display the result.

## Part B: Normalization and Comparison

In this part, we normalize the data and compare the mean squared errors with the baseline model.

### Part B Steps:
- Normalize the data using StandardScaler.
- Split the normalized data into training and test sets.
- Build and train the neural network model on normalized data.
- Predict using the trained model.
- Calculate the normalized Mean Squared Error and compare it with the baseline model.

## Part C: Increase Epochs and Comparison

Here, we increase the number of training epochs and compare the mean squared errors with previous steps.

### Part C Steps:
- Repeat the process with 100 training epochs.
- Compare the normalized Mean Squared Errors between 50 and 100 epochs.

## Part D: Three Hidden Layers and Comparison

Finally, we use a neural network with three hidden layers and compare its performance to previous models.

### Part D Steps:
- Build and train a neural network with three hidden layers.
- Predict using the trained model.
- Calculate the normalized Mean Squared Error and compare it with the previous models.

## Analysis and Conclusion

We analyze the results from each part and draw meaningful conclusions about the performance of different neural network configurations.

## Prerequisites

- Python
- pandas
- numpy
- scikit-learn
- keras

## Usage

1. Clone or download the repository.
2. Make sure you have the required libraries installed (`pip install pandas numpy scikit-learn keras`).
3. Run the provided Python script step by step, following the instructions in each section.
4. Analyze the output and results for each part to understand the effects of different model configurations.

## Acknowledgments

This analysis is based on the "Concrete Strength Prediction" project from Cognitive Class's Deep Learning course.
