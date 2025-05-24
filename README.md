# Breast Cancer Classification Using Machine Learning

This project presents a comparative analysis of Logistic Regression, Random Forest, Support Vector Machine (SVM), and Ensemble techniques to classify breast cancer using the Breast Cancer Coimbra dataset. The work was completed as part of my course project for DA5030.

---

## Dataset

The project uses the publicly available **Breast Cancer Coimbra dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra). It includes 116 patient records with 9 clinical features and a binary classification target.

---

## Getting Started

These instructions will help you view the analysis, model evaluations, and visualizations on your local machine.

### Prerequisites

- Any modern web browser (to view the `.html` notebook)
- PDF reader (to view the final report)

### Optional (to rerun code)
- R with packages:
  - `caret`
  - `randomForest`
  - `e1071`
  - `ggplot2`
  - `tidyverse`

---

## Installing

Clone the repository and open the notebook or report directly:

```bash
git clone https://github.com/JigyasaS21/breast-cancer-ml-classification.git
cd breast-cancer-ml-classification
```

## Highlights

- **Data Cleaning & Normalization**: Outlier removal, Min-Max scaling, and log-transformation
- **Feature Engineering**: PCA, glucose-insulin ratio
- **Model Training**: Logistic Regression, Random Forest, SVM
- **Model Evaluation**: Confusion matrices, ROC-AUC, Accuracy, F1-score
- **10-Fold Cross Validation** and **Hyperparameter Tuning**
- **Ensemble Modeling and Bagging** for improved performance

---

## Results

### 📊 Model Performance Interpretation

| Model              | Accuracy | Balanced Accuracy | AUC   | Kappa |
|-------------------|----------|-------------------|-------|--------|
| Logistic Regression | 81.2%    | 81.7%             | 0.817 | 0.613  |
| SVM (RBF)           | 81.2%    | 81.7%             | 0.817 | 0.613  |
| Random Forest       | 56.2%    | 58.3%             | 0.583 | 0.152  |

---

## Author

**Jigyasa Saini**  
MS Bioinformatics  
Northeastern University  
2025
