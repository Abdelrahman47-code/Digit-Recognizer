# Digit-Recognizer
This is the repo for my second task as an Artificial Intelligence Intern at SYNC INTERN'S. Digit Recognizer is a CNN model to predict handwritten digits (0 to 9).
The task passed through different steps such as Data Preprocessing, Building the CNN model, Data Augmentation, Learning Rate Scheduling, Regularization (Dropout), and Early Stopping.
After that, Evaluating the model, saving it, and the final step (prediction).

# Digit Recognition with Deep Learning

[![Python Version](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9-blue)](https://www.python.org/downloads/)

Aspiring to explore the world of deep learning and enhance my skills, I embarked on a captivating journey to create a powerful digit recognition model using the famous MNIST dataset. This project demonstrates the step-by-step process of building, training, and evaluating a Convolutional Neural Network (CNN) model to recognize handwritten digits.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Visualization](#data-visualization)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Making Predictions](#making-predictions)
- [Interactive Bar Chart](#interactive-bar-chart)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to accurately recognize handwritten digits using a deep learning approach. The MNIST dataset contains 28x28 grayscale images of digits from 0 to 9. The project explores various techniques such as data augmentation, learning rate scheduling, dropout regularization, early stopping, and more to improve the model's accuracy and generalization.

## Installation

1. Clone this repository to your local machine using `git clone https://github.com/your-username/digit-recognition.git`
2. Navigate to the project directory: `cd digit-recognition`
3. Install the required Python packages: `pip install -r requirements.txt`

## Usage

1. Run the Jupyter Notebook `digit_recognition.ipynb` to explore the step-by-step implementation.
2. Use the provided Python script `predict_digit.py` to interactively draw digits and make predictions.

## Data Visualization

- Visualize the distribution of digit labels using horizontal and pie charts.

## Data Preprocessing

- Normalize pixel values to [0, 1].
- Convert labels to one-hot encoded vectors.
- Implement data augmentation techniques to enhance training samples.

## Model Architecture

- Create a CNN model with convolutional, pooling, and dense layers.
- Introduce dropout regularization to prevent overfitting.

## Training

- Train the model using the training dataset.
- Utilize early stopping and model checkpoint callbacks.

## Evaluation

- Evaluate the model using the validation dataset.
- Generate a confusion matrix to analyze model performance.

## Making Predictions

- Preprocess user-drawn images for digit prediction.
- Use the trained model to make predictions.

## Interactive Bar Chart

- Create an interactive bar chart using Plotly to explore the label distribution.

## Conclusion

This hands-on project in digit recognition using deep learning was an exhilarating experience. The use of various techniques, coupled with model evaluation and interactive visualizations, enabled the creation of a robust digit recognition model. The project serves as a stepping stone for exploring deep learning applications and continues to inspire further exploration in the world of AI.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## Dataset
https://www.kaggle.com/competitions/digit-recognizer)https://www.kaggle.com/competitions/digit-recognizer
