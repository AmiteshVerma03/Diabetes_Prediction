# 🩺 Diabetes Prediction Using Support Vector Machine (SVM)

This project demonstrates how to predict diabetes using the Pima Indians Diabetes dataset and Support Vector Machines (SVM). It includes data exploration, preprocessing with standardization, model training using `SVC`, and performance evaluation using accuracy and recall metrics.

## 🎯 Objectives

- Understand and visualize the dataset
- Standardize feature values
- Train a linear SVM classifier
- Evaluate the model using appropriate metrics

## 📁 Files

- `Diabetes.ipynb` – Main Jupyter notebook for data preprocessing, model building, and evaluation.

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib

## 🔍 Workflow

1. **Data Loading & Exploration**
   - Dataset loaded from `diabetes.csv`
   - Visualized using seaborn pairplot
   - Statistical insights like mean values grouped by outcome

2. **Preprocessing**
   - Features and labels separated
   - Features standardized using `StandardScaler`
   - Stratified train-test split (80/20)

3. **Model Training**
   - Linear `SVC` (Support Vector Classifier) from scikit-learn used
   - Fitted on the training data

4. **Evaluation**
   - Confusion matrix, accuracy, and recall used for model evaluation

## 📊 Results

- The model provides baseline metrics using simple SVM.
- Accuracy and recall were computed on the test set to evaluate real-world performance.

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/AmiteshVerma03/diabetes-prediction-svm.git
cd diabetes-prediction-svm
