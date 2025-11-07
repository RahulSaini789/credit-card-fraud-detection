## Results Summary

| Model | Recall (Fraud) | Precision (Fraud) | F1 | Threshold |
|-------|-----------------|-------------------|----|------------|
| Logistic Regression (Scaled) | ~0.69 | ~0.85 | ~0.76 | 0.50 |
| Random Forest (Default) | 0.77 | 0.96 | 0.85 | 0.50 |
| Random Forest (Tuned) | 0.83 | 0.94 | 0.88 | 0.30 |

The tuned Random Forest model achieved the best balance, catching ~83 % of fraudulent transactions while maintaining 94 % precision. Threshold tuning proved more effective than model complexity alone, reinforcing that calibration matters more than chasing higher accuracy.
