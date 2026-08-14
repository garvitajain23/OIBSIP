# Iris Flower Classification

## 📌 Task 1 — Iris Flower Classification

### Objective

The objective of this project is to build a machine learning classification model that can identify the species of an iris flower based on its physical measurements.

The model classifies iris flowers into three species:

* **Setosa**
* **Versicolor**
* **Virginica**

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Google Colab / Jupyter Notebook**

---

## 📊 Dataset

The **Iris dataset** is obtained directly from `sklearn.datasets`, so no external dataset download is required.

The dataset contains **150 samples** with four numerical features:

| Feature      | Description               |
| ------------ | ------------------------- |
| Sepal Length | Length of the sepal in cm |
| Sepal Width  | Width of the sepal in cm  |
| Petal Length | Length of the petal in cm |
| Petal Width  | Width of the petal in cm  |

There are three target classes:

* Setosa
* Versicolor
* Virginica

---

## 🔍 Exploratory Data Analysis

The following EDA steps are performed:

* Dataset shape
* Data types
* Null value checking
* Descriptive statistics
* Species distribution

---

## 📈 Data Visualisation

The project includes:

* **Pairplot** to visualize relationships between features and species
* **Box plots** to examine feature distributions and identify differences between species

These visualizations help understand which features are most useful for classification.

---

## 🎯 Feature Selection Discussion

Based on the visualizations, **petal length and petal width** provide strong separation between the three iris species.

In particular, Setosa is clearly separated from the other two species using petal measurements. Versicolor and Virginica also show considerable separation based on petal length and petal width.

Therefore, petal-related features are among the most discriminative features in this dataset.

---

## 🤖 Machine Learning Models

Two classification algorithms are trained and evaluated:

### 1. Logistic Regression

Logistic Regression is used as a simple and effective baseline classification algorithm.

### 2. K-Nearest Neighbours (KNN)

KNN classifies a new sample based on the classes of its nearest training samples.

---

## 🔀 Train-Test Split

The dataset is divided into:

* **80% Training data**
* **20% Testing data**

`train_test_split` from Scikit-learn is used for splitting the dataset.

---

## 📏 Model Evaluation

Each model is evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**

  * Precision
  * Recall
  * F1-score

The performance of both models is compared to identify the best-performing classifier.

---

## 🏆 Best Model

The model with the highest test accuracy and strong precision, recall, and F1-score is selected as the **best-performing model**.

The final notebook contains the actual evaluation results and justification for selecting the best model.

---

## 📁 Project Structure

```text
Iris-Flower-Classification/
│
├── Iris_Flower_Classification.ipynb
└── README.md
```

---

## ▶️ How to Run

1. Open the Jupyter Notebook in **Google Colab** or Jupyter Notebook.
2. Run the cells sequentially from top to bottom.
3. The Iris dataset will be loaded automatically using Scikit-learn.
4. Perform EDA and visualizations.
5. Train the classification models.
6. Compare their evaluation results.
7. Identify the best-performing model.

---

## ✅ Task Checklist

* [x] Load Iris dataset using `sklearn.datasets.load_iris()`
* [x] Perform Exploratory Data Analysis
* [x] Check shape and data types
* [x] Check for null values
* [x] Generate descriptive statistics
* [x] Create feature visualizations
* [x] Create box plots
* [x] Discuss feature selection
* [x] Perform 80/20 train-test split
* [x] Train at least two classifiers
* [x] Evaluate accuracy
* [x] Generate confusion matrices
* [x] Generate classification reports
* [x] Compare model performance
* [x] Identify the best-performing model

---

## 📌 Conclusion

This project demonstrates the complete machine learning workflow for a classification problem, starting from data loading and exploratory analysis to visualization, model training, evaluation, and model selection.

The Iris dataset provides a simple example of how machine learning algorithms can classify data into multiple categories based on numerical features.
