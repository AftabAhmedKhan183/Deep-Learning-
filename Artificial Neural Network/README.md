# Artificial Neural Network (ANN)

This notebook explores the implementation of an **Artificial Neural Network (ANN)** for multiclass classification using the **Iris dataset**.

It covers the preprocessing pipeline, Perceptron-based classification, and an ANN built using TensorFlow/Keras.

## Dataset

The notebook uses the **Iris dataset**, containing measurements of iris flowers.

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The dataset contains **150 samples**, with 50 samples belonging to each class.

## Topics Covered

- Loading and exploring a dataset
- Understanding class distribution
- Data visualization
- Feature selection
- Label Encoding
- Train-Test Split
- Feature Standardization
- Perceptron
- Artificial Neural Network
- Dense layers
- Activation functions
- ReLU
- Softmax
- Categorical classification
- Model training
- Model evaluation
- Classification metrics

## Preprocessing

The notebook performs several preprocessing steps before training the models:

1. Loads the Iris dataset.
2. Examines the dataset and class distribution.
3. Separates input features and target labels.
4. Encodes the categorical target.
5. Splits the data into training and testing sets.
6. Standardizes the input features.

## Perceptron

A Scikit-learn `Perceptron` model is trained on the processed Iris data.

This provides an introduction to a basic neural classification model before moving to a multi-layer Artificial Neural Network.

## Artificial Neural Network

The notebook then builds an ANN using **TensorFlow/Keras**.

The network uses:

- Input layer
- Dense layers
- ReLU activation
- Softmax output layer

The model is trained for multiclass classification using an appropriate classification loss.

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## Learning Outcomes

After completing this notebook, the following concepts are practiced:

- Preparing data for neural networks
- Encoding categorical labels
- Standardizing numerical features
- Understanding the Perceptron
- Building an ANN with Keras
- Understanding Dense layers
- Using ReLU for hidden layers
- Using Softmax for multiclass output
- Training and evaluating neural networks
- Comparing basic neural classification with an ANN

## Technologies

```text
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow
Keras
Google Colab
```

## Notebook

`Artificial_Neural_Network_ANN.ipynb`
