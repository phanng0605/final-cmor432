# Supervised Learning

This folder contains Jupyter notebooks demonstrating key **supervised** machine learning algorithms **using** scikit‑learn.

## Notebooks Included
- **perceptron_library.ipynb**: Binary classification on the Iris dataset (Setosa vs. Versicolor) using `Perceptron`.
- **linear_regression_library.ipynb**: Regression on the California Housing dataset using `LinearRegression`.
- **logistic_regression_library.ipynb**: Binary classification on the Pima Indians Diabetes dataset using `LogisticRegression`.
- **neural_networks_library.ipynb**: Multi‑class digit classification on the Digits dataset using `MLPClassifier`.
- **knn_library.ipynb**: Wine classification using `KNeighborsClassifier`.
- **decision_trees_library.ipynb**: Titanic survival prediction using `DecisionTreeClassifier`.
- **random_forests_library.ipynb**: Income classification (>50K vs. ≤50K) on the Adult dataset using `RandomForestClassifier`.
- **boosting_library.ipynb**: Breast cancer prediction using `AdaBoostClassifier`.

## How to Run
1. Ensure you have the root-level environment set up:
   ```bash
   pip install -r ../requirements.txt
2. Launch the notebook's kernel
3. Navigate to this folder and open any notebook.
4. Run cells sequentially to reproduce data loading, training, evaluation, and visualization steps.