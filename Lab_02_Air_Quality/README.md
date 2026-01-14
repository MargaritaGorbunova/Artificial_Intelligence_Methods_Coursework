# Lab 02: Air Quality Classification

**Task:** Multiclass classification predicting air quality category from 9 environmental parameters.

**Methods:**

- Multi-layer perceptron (3 hidden layers: 128→64→32, ReLU activation)
- Dropout regularization (p=0.2)
- Class-weighted CrossEntropyLoss for imbalanced data
- Adam optimizer (lr=0.001)

**Dataset:** 5,000 samples × 10 features from custom collection
- Features: Temperature, Humidity, PM2.5, PM10, NO2, SO2, CO, Proximity_to_Industrial_Areas, Population_Density
- Target: Air Quality (Good/Moderate/Poor/Hazardous)
- Class distribution: 2000/1500/1000/500 (40%/30%/20%/10%)

**Results:**

| Model | Test Accuracy | Test Loss | Epochs | Class Weighting |
|-------|---------------|-----------|--------|-----------------|
| MLP (128-64-32) | 92.14% | 0.1967 | 50 | Yes |

**Class Weights Applied:**
- Good (40%): 0.629
- Moderate (30%): 0.829
- Poor (20%): 1.229
- Hazardous (10%): 2.571

**Implementation:** Complete PyTorch implementation with preprocessing, training pipeline, and evaluation.

**Files:**

- `air_quality_classification.ipynb` (all code + visualizations)
- `updated_pollution_dataset.csv` (data: 5,000 samples)
