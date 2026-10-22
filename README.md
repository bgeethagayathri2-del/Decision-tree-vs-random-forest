# Decision Tree vs Random Forest

Compares a single decision tree with a random forest (many trees) on classifying wines into 3 types.

- **Dataset:** Wine (from scikit-learn)
- **Results:**

| Model | Test accuracy | Cross-validation accuracy |
|---|---|---|
| Decision Tree | 0.944 | 0.871 |
| Random Forest | 1.000 | 0.972 |

- **Conclusion:** Random Forest performed better than a single Decision Tree on both tests. The cross-validation score (average over 5 different splits) is the fairer comparison: 97.2% for Random Forest against 87.1% for the Decision Tree. A forest combines many trees, so it makes fewer mistakes than one tree on its own.

## Key Finding
The most important features for telling the wine types apart were flavanoids (20.2%), color intensity (17.1%) and proline (13.9%).

## How to run
Open `Tree_vs_forest.ipynb` in Google Colab and click Run all.
