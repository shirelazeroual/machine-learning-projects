# Machine Learning Projects

Machine learning notebooks in Python (pandas, scikit-learn, matplotlib, seaborn), written for the Machine Learning course of my B.Sc. in Computer Science at SCE (Sami Shamoon College of Engineering).

## Projects

| Folder | Task | Models |
|---|---|---|
| [01-classification-and-regression](01-classification-and-regression) | Breast cancer detection (classification) and California house prices (regression), with EDA | Logistic Regression, KNN, Decision Tree (classifier and regressor), Linear Regression |
| [02-machine-failure-prediction](02-machine-failure-prediction) | Predict whether an industrial machine will fail, from sensor data (~136,000 records) | Logistic Regression, KNN (k = 3, 5, 7, 9), Decision Tree (depth 3, 5, 7, 10) |

## Highlights

- **Classification and regression:** Logistic Regression gave the best accuracy and F1 score on breast cancer detection; the KNN regressor gave the lowest MSE and highest R² on house prices. The notebook also explains why scaling matters for KNN (distance-based) but not for decision trees (threshold splits).
- **Machine failure prediction:** the data is highly imbalanced (about 1.6% failures), so accuracy alone is misleading: a model can reach 98% accuracy while missing almost every failure. The notebook compares models on precision, recall and confusion matrices, and measures how removing the binary failure-type features and the most important feature changes the results.

## How to run

Open the notebooks in Jupyter or Google Colab. Notebook 01 uses datasets built into scikit-learn. Notebook 02 expects the `train.csv` file of the machine failure dataset, which is not included in this repository.

The notebook comments in project 02 are in Hebrew.

## Author

Shirel Azeroual · Computer Science student, SCE
