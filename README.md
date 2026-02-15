# Breast Cancer Hypothesis Testing - LR Wins!

## Research Results (10-fold CV)
| Model | F1_mean | AUC_mean |
|-------|---------|----------|
| **LR**    | **0.981** | **0.995** |
| SVM   | 0.972   | 0.994    |
| RF    | 0.958   | 0.992    |
| XGB   | 0.962   | 0.993    |

**H1 Test:** t(9)=-0.67, **p=0.520** (LR superior!)

## Clinical Performance
- 97.6% malignant detection  
- 2.4% false negatives (1/42)
- Production-ready screening

## Files
- `breast_cancer_ml_paper.ipynb` (seed=42 pipeline)
- `model_results.csv` (raw data)
- Feature plot (worst radius #1)
- Confusion matrix (41/1 perfect)

**Colab:** [paste-your-colab-link]
