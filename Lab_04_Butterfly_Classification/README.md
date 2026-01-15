# **Lab 04: Butterfly Species Image Classification**

**Task:** Multiclass image classification of 75 butterfly species from 130×130 RGB images.

**Methods:**
* Convolutional Neural Network (4 convolutional layers, batch normalization, dropout)
* Data augmentation pipeline (rotation, shifts, flipping)
* TensorFlow/Keras implementation with ImageDataGenerator

**Dataset:** Butterfly Image Classification - 6,499 images (130×130 pixels)
* Training: 5,199 samples
* Validation: 650 samples
* Testing: 650 samples
* Classes: 75 butterfly species

**Results:**
| Model | Test Accuracy | Epochs | Training Time | Parameters |
|-------|---------------|--------|---------------|------------|
| CNN | **74.92%** | 25 | ~11 minutes | 1,025,195 |

**Additional Metrics:**
* **Best Validation Accuracy:** 74.00%
* **Final Training Accuracy:** 83.73%
* **Overfitting Gap:** 9.73%
* **Best Epoch:** 25

**Implementation:** Complete TensorFlow/Keras implementation with data preprocessing, model training, evaluation, visualization, and comprehensive analysis.

**Files:**
* `butterfly_classification_cnn.ipynb` (all code + visualizations + confusion matrices + training curves)
