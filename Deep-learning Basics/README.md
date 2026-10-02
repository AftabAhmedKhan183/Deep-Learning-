# Deep Learning Basics

This notebook introduces the fundamental concepts and workflow used in Deep Learning with **Python, TensorFlow, Keras, NumPy, Pandas, and Scikit-learn**.

## Topics Covered

- Preparing data for a neural network
- Feature selection
- Min-Max feature scaling
- Training and testing data
- Neural network model using Keras
- Dense layers
- Binary classification
- Model compilation and training
- Loss and accuracy
- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent
- Momentum-based optimization
- Comparing different training approaches

## Dataset

A small custom dataset is created using:

- `soil_moisture`
- `temperature_c`
- `sunlight_hours`
- `needs_water`

The model uses the environmental features to predict whether the plant **needs water**.

## Libraries Used

- NumPy
- Pandas
- TensorFlow
- Keras
- Scikit-learn

## Model

The notebook uses a neural network built with Keras and explores different training configurations by changing the batch size.

The training approaches explored include:

### Batch Gradient Descent

The complete training dataset is used for each parameter update.

### Stochastic Gradient Descent

The model is trained with a batch size of `1`, updating the parameters after each training example.

### Mini-Batch Gradient Descent

A batch containing multiple training examples is used for each update.

## Learning Outcomes

After completing this notebook, the following concepts are practiced:

- Preparing tabular data for Deep Learning
- Scaling numerical features
- Creating a basic neural network with Keras
- Understanding epochs and batch size
- Understanding different forms of Gradient Descent
- Observing training and validation performance
- Understanding the role of optimization during neural network training

## Technologies

```text
Python
NumPy
Pandas
Scikit-learn
TensorFlow
Keras
Google Colab
```

## Notebook

`Deep_Learning_Basics.ipynb`
