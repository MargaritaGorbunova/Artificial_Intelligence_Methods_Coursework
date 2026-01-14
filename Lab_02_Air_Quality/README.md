Lab 01: Concrete Strength Prediction
Task: Regression predicting concrete compressive strength from 8 material parameters.

Methods:

Single-layer perceptron (Widrow-Hoff algorithm with early stopping)
Multi-layer perceptron (1 hidden layer, ReLU, backpropagation)
Dataset: 1,030 samples × 9 features from Kaggle

Results:

Model	Test MSE	Epochs	Improvement
Single-layer	100.15	27*	Baseline
Multi-layer	95.93	100	-4.2%
*Early stopping

Implementation: Complete from-scratch neural network implementation in single notebook.

File:

concrete_strength_prediction.ipynb (all code + visualizations)
concrete_sdata.csv (data)
