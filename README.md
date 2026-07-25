# CODEALPHA-INTERNSHIP
#  Iris Flower Classification using Machine Learning

##  Project Overview

This project builds and evaluates multiple Machine Learning models to classify Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The classification is based on four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The project includes data preprocessing, exploratory data analysis (EDA), model training, hyperparameter tuning, evaluation, and comparison of multiple classification algorithms.

---

##  Objectives

- Classify Iris flowers based on their measurements.
- Perform Exploratory Data Analysis (EDA).
- Train multiple Machine Learning classification models.
- Compare model performances using evaluation metrics.
- Tune model parameters using GridSearchCV.
- Select the best-performing model.

---

##  Dataset

The dataset contains measurements of Iris flowers with the following features:

| Feature | Description |
|---------|-------------|
| Sepal Length | Length of the sepal (cm) |
| Sepal Width | Width of the sepal (cm) |
| Petal Length | Length of the petal (cm) |
| Petal Width | Width of the petal (cm) |
| Species | Target class |

Target Classes:

- Setosa
- Versicolor
- Virginica

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- sklearn.model_selection
- sklearn.preprocessing
- sklearn.pipeline
- sklearn.metrics
- sklearn.linear_model
- sklearn.neighbors
- sklearn.tree
- sklearn.ensemble
- sklearn.svm

---

##  Exploratory Data Analysis

The project performs:

- Dataset overview
- Missing value detection
- Duplicate value detection
- Statistical summary
- Class distribution
- Histograms
- Boxplots
- Correlation Heatmap
- Pairplot

---

##  Machine Learning Models

The following models are trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier

---

##  Hyperparameter Tuning

The project uses **GridSearchCV** to find the best parameters for selected models.

---

##  Evaluation Metrics

Each model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Cross Validation Score
- Confusion Matrix

---

## 📉 Model Comparison

The performance of all trained models is compared using:

- Accuracy Comparison Chart
- Cross Validation Scores

This helps identify the best-performing classifier.

---

## 📁 Project Structure

```
Iris-Flower-Classification/
│
├── Iris_Classification.ipynb
├── Iris.csv
├── outputs/
│   ├── correlation_heatmap.png
│   ├── pairplot.png
│   ├── model_comparison.png
│   └── confusion_matrix.png
├── results.csv
├── requirements.txt
└── README.md
```

---

##  How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Iris-Flower-Classification.git
```

### Navigate to the project folder

```bash
cd Iris-Flower-Classification
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
Iris_Classification.ipynb
```

using:

- Jupyter Notebook
- Google Colab
- VS Code

---

## 📌 Results

The project successfully classifies Iris flowers with high accuracy using multiple machine learning algorithms.

Among the evaluated models, the best-performing classifier is selected based on evaluation metrics and cross-validation performance.

---

## 🚀 Future Improvements

- Deploy the model using Streamlit or Flask
- Add an interactive prediction interface
- Experiment with additional classification algorithms
- Use feature selection techniques
- Perform model explainability using SHAP or LIME

---

## 👨‍💻 Author

**Hassan Baig**

Artificial Intelligence & Data Science Student

---

## 📜 License

This project is developed for educational and learning purposes.
