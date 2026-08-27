# INIB
# Intern Infobyte – Machine Learning Internship

This repository contains the machine learning task completed as part of my **Machine Learning Internship at Intern Infobyte**.

## 📌 Task Completed

### Task 1 – Iris Flower Classification

The objective of this project is to build a machine learning classification model that predicts the species of an Iris flower based on its physical measurements.

The project uses the famous **Iris dataset** and applies the **K-Nearest Neighbors (KNN)** classification algorithm.

## 📂 Repository Structure

```text
INIB/
│
├── Iris-Flower-Classification/
│   ├── Iris_Flower_Classification.ipynb
│   ├── README.md
│   └── requirements.txt
│
└── README.md
```

## 🧠 Project Overview

The Iris dataset contains measurements of Iris flowers belonging to three different species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

The model uses the following four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The goal is to classify a flower into its correct species based on these measurements.

## 🔧 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## 🤖 Machine Learning Algorithm

### K-Nearest Neighbors (KNN)

K-Nearest Neighbors is a supervised machine learning algorithm used for classification and regression.

For this project, KNN classification is used with:

```text
Number of Neighbors (K) = 3
```

The algorithm predicts the class of a new flower based on the classes of its nearest training examples.

## 🔍 Project Workflow

The project follows these major steps:

1. Import required Python libraries.
2. Load the Iris dataset using Scikit-learn.
3. Convert the dataset into a Pandas DataFrame.
4. Explore the dataset.
5. Check the dataset shape and data types.
6. Perform statistical analysis.
7. Check for missing values.
8. Check and remove duplicate records.
9. Perform exploratory data analysis and visualization.
10. Analyze feature relationships using correlation.
11. Split the data into training and testing sets.
12. Train a K-Nearest Neighbors classifier.
13. Generate predictions on the test data.
14. Evaluate the model using accuracy, precision, recall and confusion matrix.

## 📊 Dataset

The project uses the built-in Iris dataset provided by Scikit-learn.

The dataset contains:

* **150 observations**
* **4 numerical features**
* **3 target classes**

The four input features are:

| Feature      | Description                        |
| ------------ | ---------------------------------- |
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width  | Width of the sepal in centimeters  |
| Petal Length | Length of the petal in centimeters |
| Petal Width  | Width of the petal in centimeters  |

Target classes:

| Class      |
| ---------- |
| Setosa     |
| Versicolor |
| Virginica  |

## 📈 Exploratory Data Analysis

The notebook performs several exploratory data analysis steps, including:

* Dataset inspection
* Statistical summary
* Missing-value analysis
* Duplicate-value analysis
* Distribution analysis
* Feature visualization
* Correlation analysis
* Pairwise feature visualization

These steps help understand the structure and relationships within the dataset before model training.

## 🧪 Model Training

The dataset is divided into training and testing data.

The KNN classifier is configured with:

```python
KNeighborsClassifier(n_neighbors=3)
```

The trained model is then used to predict the Iris species for unseen test samples.

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Results

| Metric    | Result |
| --------- | -----: |
| Accuracy  |   100% |
| Precision |   1.00 |
| Recall    |   1.00 |
| F1-score  |   1.00 |

The classification report contains 30 test samples, with precision, recall and F1-score of **1.00 for all three classes**.

## 🎯 Conclusion

The K-Nearest Neighbors model successfully classified the Iris flower species in the test set.

The model achieved:

**100% Accuracy**

with:

**1.00 Precision and 1.00 Recall**

for Setosa, Versicolor and Virginica on the recorded test set.

This project demonstrates the complete workflow of a basic supervised machine learning classification problem, from dataset exploration and preprocessing to model training and evaluation.

## 🚀 How to Run

### Option 1 – Google Colab

Open the notebook in Google Colab and run the cells sequentially.

### Option 2 – Local Environment

Clone this repository and install the required dependencies:

```bash
pip install -r requirements.txt
```

Then open:

```text
Iris_Flower_Classification.ipynb
```

using Jupyter Notebook or JupyterLab.

## 👩‍💻 Internship

**Internship:** Machine Learning Internship
**Organization:** Intern Infobyte
**Task:** Iris Flower Classification

## 📌 Author

**Mansi Gite**

B.Tech – Artificial Intelligence

## ⭐ Acknowledgement

This project was completed as part of the **Intern Infobyte Machine Learning Internship**.

