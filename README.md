# Model Fairness, Bias and Explainability Analysis
## Overview
This project analyzes model fairness, bias, and explainability using SHAP.

## Explainability
SHAP summary plots were generated to understand feature importance and individual feature contributions.

## Bias Analysis
Accuracy by Gender:
- Female: 0.927
- Male: 0.814
The model performs better for Female samples compared to Male samples, indicating possible bias.
## Mitigation Strategies
- Rebalancing the dataset
- Reweighting samples
- Fairness-aware training methods
- Threshold adjustment
## How to Run
1. Install dependencies:
pip install shap scikit-learn pandas matplotlib

2. Open the notebook and run all cells.b
