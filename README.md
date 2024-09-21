# Handwritten Digit Detection using Artificial Neural Networks

This project demonstrates a neural network model to detect handwritten digits from the MNIST dataset. The model is built using Keras and TensorFlow libraries, and trained to classify digits (0-9) using fully connected layers.

## Dataset
- **MNIST Dataset:** Contains 60,000 training images and 10,000 test images of handwritten digits (28x28 pixels each).

## Libraries Used
- `TensorFlow`
- `Keras`
- `NumPy`
- `Matplotlib`
- `Seaborn`

## Model Architecture
- Flattened 28x28 input images to a 784-dimensional vector.
- 1 or 2 hidden dense layers with sigmoid activation.
- Output layer with 10 units and softmax activation for multi-class classification.

## Training
- Loss function: `sparse_categorical_crossentropy`
- Optimizer: `Adam`
- Metric: `accuracy`
- Trained over 5 epochs.

## Results

- A confusion matrix was used to evaluate classification performance visually.


