# DecisionTree_KNN-sklearn-_Performance-Evaluation-Programming 

## 📝 Overview  
This repository features three Jupyter notebooks showcasing core supervised learning methods using scikit-learn.  
Each notebook is clearly annotated with beginner-friendly explanations, guiding you through building, evaluating, and interpreting machine learning models.

---

**Name:** SHASHANK REDDY DASARI  
**ID:** 700781569  

---
# 📘 Notebooks Overview  

## 1. DecisionTree_sklearn.ipynb  

**Goal:** Decision Trees on the Iris dataset.  

### Steps  
- Load the Iris dataset and divide it into training and testing sets.  
- Train `DecisionTreeClassifier` models with `max_depth = 1, 2, 3`.  
- Measure and report training and test accuracy for each depth.  
- Analyze **underfitting vs. overfitting** by looking at accuracy gaps and tree complexity.  
- Visualize the trained decision trees along with their decision boundaries.  

### Key Insights  
- Shallow trees (depth = 1) underfit, leading to low train and test accuracy.  
- Moderately deep trees tend to generalize well.  
- Very deep trees may overfit if training accuracy is much higher than test accuracy.  

---

## 2. kNN_Classification_sklearn.ipynb  

**Goal:** Show how k-Nearest Neighbors (kNN) behaves with different values of **k**.  

### Steps  
- Use only two features from Iris (sepal length and sepal width) for visualization purposes.  
- Train kNN models with `k = 1, 3, 5, 10`.  
- Plot decision boundaries for each **k** to demonstrate how neighborhood size impacts classification.  
- Explain how the boundaries evolve as **k** increases.  

### Key Insights  
- **k=1:** extremely flexible, jagged boundaries → low bias, high variance (risk of overfitting).  
- **k=3,5:** smoother boundaries with better generalization.  
- **k=10:** very smooth boundaries which may underfit if **k** is too large.  

---

## 3. Performance_Evaluation.ipynb  

**Goal:** Evaluate classifiers using multiple performance metrics.  

### Steps  
- Train a kNN classifier (`k=5`) on the Iris dataset.  
- Compute and plot the confusion matrix.  
- Generate a classification report (precision, recall, F1, accuracy).  
- Plot ROC curves (one-vs-rest for multiclass) and calculate AUC values.  

### Key Insights  
- Confusion matrices help reveal which classes are misclassified.  
- Precision, Recall, and F1 give a more detailed evaluation than accuracy, especially for imbalanced datasets.  
- ROC and AUC visualize the trade-off between sensitivity and specificity; for multiclass problems, use one-vs-rest.  

---



