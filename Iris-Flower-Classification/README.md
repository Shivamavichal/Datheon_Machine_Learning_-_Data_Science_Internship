# Iris Flower Classification Using Machine Learning

## Project Overview
This project implements a supervised machine learning classification model to predict the species of an Iris flower using its sepal and petal measurements.

Two classification algorithms are implemented and compared:
- Logistic Regression
- Decision Tree Classifier

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and explore the dataset.
2. Check for missing values and understand the data.
3. Visualize the dataset using pairplots and countplots.
4. Separate the input features and target variable.
5. Split the dataset into training and testing sets (80:20).
6. Apply feature scaling using StandardScaler.
7. Train Logistic Regression and Decision Tree models.
8. Evaluate both models using accuracy, precision, recall, and F1-score.
9. Visualize confusion matrices and decision boundaries.

## Folder Structure
```text
Iris-Flower-Classification/
├── dataset/
│   └── Iris.csv
├── notebooks/
│   └── iris_classification.ipynb
├── images/
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project folder:
   ```bash
   cd Iris-Flower-Classification
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `notebooks/iris_classification.ipynb` and run the cells.

## Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The results help compare the classification performance of both algorithms.

## Author
Add your name here.
