**Poker Hand Classification Project**

This project aims to build a machine learning model for classifying poker hands. Given the features of five playing cards, the model predicts the type of poker hand they represent, such as one pair, two pair, or a flush.

## Dataset
The dataset used in this project is stored in the file poker_hand_test.data. It contains information about poker hands and their corresponding labels.

## Requirements
Before running the code, ensure you have the following libraries installed:
pandas
matplotlib
scikit-learn
yellowbrick

## Usage
Clone the repository to your local machine.
Ensure you have the necessary dataset file (poker_hand_test.data) in the appropriate location.
Run the Python script poker_classification.py to train the machine learning model and evaluate its performance.

## Machine Learning Model
We use a Multi-Layer Perceptron (MLP) classifier to predict poker hands. The model architecture includes multiple hidden layers with a tanh activation function.

## Evaluation
The model's performance is evaluated using various metrics, including accuracy, ROC curves, classification reports, and class prediction errors. These metrics help assess how well the model classifies different poker hands.



**Author** devanshu3