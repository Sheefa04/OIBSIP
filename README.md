 OIBSIP Task 1 - Iris Flower Classification

 📌 Project Overview

This project is part of the OASIS INFOBYTE Data Science Internship.

The objective of this project is to build a machine learning classification model that predicts the species of an iris flower using its sepal and petal measurements.

📊 Dataset

The Iris dataset is obtained from `sklearn.datasets`.

It contains 150 flower samples belonging to three species:

- Setosa
- Versicolor
- Virginica

 Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

 🔍 Exploratory Data Analysis

The following analysis was performed:

- Dataset shape and structure
- Data types
- Missing value checking
- Descriptive statistics
- Species distribution
- Pairplot
- Box plot
- Correlation heatmap

🤖 Machine Learning Models

Two classification models were used:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

 📈 Model Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| KNN | 100% |

KNN achieved the higher accuracy on the test dataset.

 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

 📁 Project Files

```text
DataScience-Task1-IrisClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
└── screenshots/
    ├── 4.1 Pair Plot.png
    ├── 4.2 Box Plot.png
    ├── 4.3 Correlation Heatmap.png
    ├── Model 1.png
    └── Model 2.png

Conclusion
The Iris flower classification problem was successfully implemented using two machine learning classification algorithms. KNN achieved 100% accuracy on the
 test dataset, while Logistic Regression achieved 96.67% accuracy.
