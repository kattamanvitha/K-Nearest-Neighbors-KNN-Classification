🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for classification using the popular Iris dataset. It includes data preprocessing, model training, evaluation, and visualization.

📌 Objective
- To understand and implement KNN for classification problems using Python.
- Explore how the value of `k` affects the classification accuracy.
- Visualize the decision boundary of the classifier.

🛠 Tools & Libraries
- Python
- Scikit-learn (`sklearn`)
- Pandas
- NumPy
- Matplotlib

 📊 Dataset
-Name:Iris Flower Dataset
- Source: Built-in dataset in `sklearn.datasets`
- Features: Sepal length, Sepal width, Petal length, Petal width
- Target Classes: Setosa, Versicolor, Virginica

 🚀 Steps Performed
1. Data Loading: Loaded the Iris dataset from `sklearn`.
2. Normalization: Applied standard scaling using `StandardScaler`.
3. Train/Test Split: Used 70% training and 30% testing data.
4. Model Building: Used `KNeighborsClassifier` from `sklearn.neighbors`.
5. Evaluation:
   - Accuracy score
   - Confusion matrix
6. Experimentation: Tested performance for `k = 1 to 20` to determine the best value.
7. Visualization:
   - Accuracy vs K plot
   - Decision boundary using first two features
