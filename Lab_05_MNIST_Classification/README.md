# Lab 05: MNIST Digit Classification

**Task:** Multiclass classification of handwritten digits (0-9) from 28×28 grayscale images.

**Methods:**
* CNN with 2 convolutional layers, max pooling
* Data augmentation (rotation, shifts, shear, zoom, flipping)
* TensorFlow/Keras with ImageDataGenerator

**Dataset:** 70,000 images (28×28 pixels)
* Training: 48,000 | Validation: 12,000 | Testing: 10,000
* Classes: 10 digits (0-9)

**Architecture:** 225,034 parameters - efficient design for digit recognition

**Results:**
| Model | Test Accuracy | Parameters | Training Time |
|-------|---------------|------------|---------------|
| CNN | **96.27%** | 225,034 | ~3 min (5 epochs) |

**Key Metrics:**
* Validation Accuracy: 96.22%
* Training Accuracy: 92.77%
* Overfitting Gap: -3.45% (no overfitting)
* Excellent performance on benchmark dataset

**Files:** `mnist_digit_classification.ipynb` (complete implementation)
