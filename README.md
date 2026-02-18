# Automated_Pneumonia_Detection
A CNN architecture trained on an imbalanced Kaggle dataset. Key Strategy: Since "Normal" and "Pneumonia" cases are unevenly distributed, the model prioritizes High Recall (minimizing missed cases) over simple accuracy. Method: Class-Weighted Cross-Entropy (Weights: Normal: 1.94, Pneumonia: 0.67) was implemented to handle data imbalance.
