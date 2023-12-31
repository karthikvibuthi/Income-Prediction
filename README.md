# Income-Prediction

<img width="966" alt="Screenshot 2023-12-31 at 7 03 40 AM" src="https://github.com/karthikvibuthi/Income-Prediction/assets/141452458/cbec512f-6807-45ed-a6b4-eee9be6504bd">
## Introduction

This project focuses on predicting high and low incomes using classification algorithms on a dataset sourced from [DATA602repo](https://github.com/cvrg-iyte/DATA602repo). The goal is to distinguish between high and low-income individuals based on various features available in the dataset.

## Dataset

The dataset used for this project is sourced from [DATA602repo](https://github.com/cvrg-iyte/DATA602repo). The file `income2.data` contains the necessary information for training and testing the classification models.

## Classification Algorithms

### Initial Model Performance

Four classification algorithms were initially employed:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Random Forest**

Evaluation metrics for each model:
- **Accuracies**: 87%, 85%, 82%, 84% respectively
- **Precisions**: 79%, 77%, 71%, 71% respectively
- **Recalls**: 62%, 55%, 46%, 60% respectively
- **F1-scores**: 69%, 64%, 56%, 65% respectively

### Advanced Techniques

Further techniques were applied to enhance model performance:

#### Grid Search and Ensembling Techniques

- **Ensemble Techniques**: Stacking Classifier, Extended Voting Classifier, Bagging with Random Forest, Boosting with Gradient Boosting
- **Performance Metrics**:
  - **Accuracy**: Ranging from 86% to 87%
  - **Low Income Precision**: 86% to 89%
  - **High Income Precision**: 78% to 81%
  - **Low Income Recall**: 94% to 96%
  - **High Income Recall**: 53% to 63%
  - **Low Income F1-Score**: 91% to 92%
  - **High Income F1-Score**: 64% to 70%

## Conclusion

The use of ensemble techniques such as stacking, voting, bagging, and boosting has improved the predictive performance of the models. These techniques have provided a more nuanced understanding of income classification, enabling higher precision and recall for both high and low-income categories.

This project demonstrates the effectiveness of ensemble methods in refining classification accuracy and expanding the scope of income prediction models.




