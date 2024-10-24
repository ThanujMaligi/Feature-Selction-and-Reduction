# Feature Selection and Reduction for Classification

## Overview
This project demonstrates the application of various **machine learning classifiers** on a dataset, comparing their performance when trained on both the full set of features and a feature-reduced dataset. The key focus is on how feature selection and dimensionality reduction techniques can influence model performance.

### Key Topics Covered:
1. **Data Preprocessing**:
   - Dataset handling and cleaning.
   - Feature selection using techniques like **PCA** or **LDA**.

2. **Classifiers**:
   - **Logistic Regression**
   - **Decision Tree**
   - **Random Forest**
   - **Support Vector Machine (SVM)**
   - **K-Nearest Neighbors (KNN)**

3. **Feature Selection and Dimensionality Reduction**:
   - Dimensionality reduction is applied to retain the most relevant features while removing noise and redundancy.
   - Helps to prevent overfitting and improves generalization.

4. **Performance Metrics**:
   - Accuracy, precision, recall, and F1-score are calculated for each classifier.
   - Comparison of model performance on the **full dataset** vs. the **feature-reduced dataset**.

## Results Summary
### Original Dataset Performance:
- Higher accuracy due to the inclusion of all features, but with a potential risk of overfitting.

### Feature-Reduced Dataset Performance:
- Reduced complexity, with slightly lower accuracy but better generalization and training efficiency.

## Conclusion
Feature selection and dimensionality reduction play a critical role in creating efficient, interpretable, and generalized models, balancing complexity with performance.

---

### How to Run
1. Download the ipynb file above.
2. Run the notebook to train and evaluate the classifiers on both datasets.
