# Comparative Analysis of Machine Learning Classifiers on the Iris Dataset

> ```
> Debargha Mitra Roy
> Department of Computer Science and Engineering
> National Institute of Technology, Durgapur
> Durgapur, Pachim Bardhaman, West Bengal 713363
> debarghamitraroy@gmail.com
> ```

[![Publication](https://img.shields.io/badge/Publication-Comparative%20Analysis%20of%20Machine%20Learning%20Classifiers%20on%20the%20Iris%20Dataset-red?style=flat&logo=googledocs&logoColor=red)](./Comparative%20Analysis%20of%20Machine%20Learning%20Classifiers%20on%20the%20Iris%20Dataset.pdf)

## 📌 Project Overview

This project presents a comparative performance analysis of multiple supervised machine learning classifiers on the famous Iris Dataset using **K-Fold Cross Validation**.

The objective is to evaluate and compare the classification performance, stability, and learning behaviour of different machine learning models using multiple evaluation metrics.

The following classifiers were implemented and analysed:

- Support Vector Machine (SVM)
- Random Forest Classifier
- Decision Tree Classifier
- Gaussian Naive Bayes
- Multilayer Perceptron (MLP)
  - 1 Hidden Layer
  - 2 Hidden Layers
  - 3 Hidden Layers

## 📂 Dataset

The project uses the **Iris Dataset** from Scikit-learn.

### Dataset Information

- Total Samples: 150
- Features: 4
- Classes: 3
  - Setosa
  - Versicolor
  - Virginica

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Evaluation Metrics

The models were evaluated using:

- Mean Accuracy
- Standard Deviation
- R² Score
- Confusion Matrix
- Accuracy vs Epoch Graph
- Loss vs Epoch Graph

## 🔄 Cross Validation

The project uses **Stratified K-Fold Cross Validation** with: $k=2-10$

This ensures:

- Better generalization
- Reduced overfitting
- Stable performance comparison

## 🧠 Implemented Models

| Model          | Description                          |
| -------------- | ------------------------------------ |
| SVM            | Linear kernel Support Vector Machine |
| Random Forest  | Ensemble-based tree classifier       |
| Decision Tree  | Tree-based classification model      |
| Naive Bayes    | Probabilistic classifier             |
| MLP (1 Layer)  | Neural Network with 1 hidden layer   |
| MLP (2 Layers) | Neural Network with 2 hidden layers  |
| MLP (3 Layers) | Neural Network with 3 hidden layers  |

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/debarghamitraroy/Comparative-Analysis-of-Machine-Learning-Classifiers-on-the-Iris-Dataset.git
```

Move into the project directory:

```bash
cd Comparative-Analysis-of-Machine-Learning-Classifiers-on-the-Iris-Dataset
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Project

Run the Jupyter Notebook:

```bash
jupyter notebook main.ipynb
```
