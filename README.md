# Permutation Importance vs SHAP for Random Forests
### Which Explanation Should You Trust?

A machine learning tutorial comparing three feature importance methods — Gini importance, permutation importance, and SHAP values — on a Random Forest trained on the Adult Income dataset.

## Learning Objectives
1. Understand how Gini (impurity-based) importance works and its known biases
2. Implement permutation importance and interpret results with confidence intervals
3. Use SHAP values for both global and local model explanations
4. Compare all three methods head-to-head and know when each is most appropriate

## Repository Structure
```
rf-feature-importance-comparison/
├── README.md
├── LICENSE (MIT)
├── requirements.txt
├── notebook/   → Jupyter tutorial notebook
├── figures/    → Generated visualisations
├── data/       → Dataset source notes
├── tutorial/   → Written tutorial report
└── references/ → Bibliography
```

## Quick Start
```bash
pip install -r requirements.txt
cd notebook/
jupyter notebook rf_feature_importance_tutorial.ipynb
```

## Author
Adil Nawaz | University of Hertfordshire | March 2026
