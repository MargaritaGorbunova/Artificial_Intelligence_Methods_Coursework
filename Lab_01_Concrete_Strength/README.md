# Lab 01: Concrete Strength Prediction

## Task
Predict concrete compressive strength based on 8 compositional parameters.

## Approach
- Implementation of single-layer and multi-layer perceptrons from scratch
- Widrow-Hoff algorithm for single-layer perceptron
- Backpropagation with ReLU activation for multi-layer perceptron
- Early stopping mechanism

## Dataset
[Concrete Compressive Strength Dataset](https://www.kaggle.com/datasets/elikplim/concrete-compressive-strength-data-set) on Kaggle

## Results
- Single-layer perceptron: Test MSE = 100.15
- Multi-layer perceptron: Test MSE = 84.53
- **Improvement: 15.6% reduction in MSE**

## Files
- `concrete_strength.ipynb` - Main notebook with implementation
- `concrete_data.csv` - Dataset
- `perceptron.py` - Custom perceptron classes
