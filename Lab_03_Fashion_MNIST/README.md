# Lab 03: Fashion MNIST Image Classification

**Task:** Multiclass image classification of 10 clothing categories from 28×28 grayscale images.

**Methods:**

- Convolutional Neural Network (2 convolutional layers, max pooling, dropout)
- Multi-layer perceptron (2 hidden layers, dropout regularization)
- TensorFlow/Keras implementation with tf.data pipeline

**Dataset:** Fashion MNIST - 70,000 images (28×28 pixels)
- Training: 60,000 samples
- Testing: 10,000 samples
- Classes: 10 clothing categories

**Results:**

| Model | Test Accuracy | Epochs | Improvement |
|-------|---------------|--------|-------------|
| MLP | 86.08% | 5 | Baseline |
| CNN | 89.38% | 5 | +3.30% |

**Implementation:** Complete TensorFlow/Keras implementation with data preprocessing, model training, evaluation, and comparative analysis.

**Files:**

- `fashion_mnist_cnn_mlp_comparison.ipynb` (all code + visualizations + confusion matrices + training curves)
