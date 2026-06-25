# 💊 Drug Classification using Support Vector Machine (SVM)

A machine learning project that predicts the appropriate drug for a patient based on their medical attributes using the **Support Vector Machine (SVM)** algorithm.

## 📌 Project Overview

This project explores the performance of different **SVM kernels** for multi-class drug classification. The dataset is preprocessed, encoded, and trained using multiple kernel functions to compare their predictive performance.

## 🚀 Features

- Data preprocessing and cleaning
- Label Encoding for categorical features
- Exploratory Data Analysis (EDA)
- Train-Test Split
- Support Vector Machine implementation
- Performance comparison across multiple SVM kernels

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The project uses the **Drug Classification Dataset**, which contains patient information such as:

- Age
- Sex
- Blood Pressure (BP)
- Cholesterol
- Sodium-to-Potassium Ratio (Na_to_K)

Target Variable:
- Drug Type

## 🤖 Model

Support Vector Machine (SVM) classifiers were trained using different kernel functions:

| Kernel | Accuracy |
|---------|----------|
| RBF (Default) | **72.5%** |
| Linear | 100% |
| Polynomial | 65.0% |
| Sigmoid | 27.5% |

> **Best baseline accuracy achieved:** **72.5% using the default RBF kernel**, without extensive hyperparameter tuning.

## 📊 Workflow

1. Load the dataset
2. Perform data preprocessing
3. Encode categorical features
4. Split data into training and testing sets
5. Train SVM models using different kernels
6. Evaluate model performance using accuracy

## 📈 Results

- Achieved **72.5% accuracy** using the **default RBF kernel**.
- Compared the performance of Linear, Polynomial, and Sigmoid kernels.
- Demonstrated how kernel selection impacts classification performance.

## 📁 Project Structure

```
├── SVM Drug Classification.ipynb
├── drug200.csv
└── README.md
```

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/drug-classification-svm.git
```

2. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

## 📚 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature scaling optimization
- Model deployment using Streamlit or Flask
- Performance evaluation using Precision, Recall, and F1-score


If you found this project helpful, feel free to ⭐ the repository.
