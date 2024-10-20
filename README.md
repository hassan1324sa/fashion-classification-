# Fashion MNIST Classification Using TensorFlow

This project implements a neural network model to classify images from the Fashion MNIST dataset using TensorFlow and Keras. The dataset contains grayscale images of clothing items, with the goal of predicting the correct category for each image.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Make sure you have the following libraries installed:

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

You can install the necessary packages using pip:

```bash
pip install tensorflow numpy matplotlib
```
---

## Dataset
The model uses the Fashion MNIST dataset, which contains 70,000 grayscale images of 10 different clothing categories. Each image is 28x28 pixels. The categories are as follows:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot
The dataset is split into 60,000 training images and 10,000 test images.
---

# Installation
1. Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/fashion-mnist-classification.git
cd fashion-mnist-classification
```
2. Make sure you have all the required libraries installed as listed above.

---

# Usage
1. Run the script
     ```bash
    python fashion_mnist_classification.py
   ```
2. The model will train for 30 epochs and evaluate its accuracy on the test dataset.
3. Predictions will be visualized, showing the predicted label, true label, and prediction probabilities for a selection of images.

--- 

# Model Architecture
The neural network model is built using the following layers:

1. Flatten Layer: Flattens the input images into a 1D array.
2. Dense Layer (512 units): Fully connected layer with ReLU activation.
3. Dense Layer (64 units): Fully connected layer with ReLU activation.
4. Dense Layer (10 units): Output layer with softmax activation for multi-class classification.
   
The model is compiled with the Adam optimizer and sparse categorical crossentropy loss.
 ---
 
# Results
  After training, the model's accuracy on the test set is printed. The script also visualizes the predictions for a set of test images, displaying the predicted class, probability,    and true label.

---

# Contributing
Feel free to contribute to this project by creating issues or submitting pull requests.
--- 

# License
This project is licensed under the MIT License. See the LICENSE file for more information.
