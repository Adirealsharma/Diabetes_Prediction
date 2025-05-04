# Diabetes_Prediction
**Diabetes Prediction** project using the PIMA dataset and an SVM model:

---

# Diabetes Prediction Project

This project is a machine learning-based system for predicting whether a person is diabetic or not using the **PIMA Indians Diabetes Dataset**. The model uses a Support Vector Machine (SVM) classifier and includes steps for data preprocessing, model training, evaluation, and prediction.

## 📂 Project Structure

* `diabetes_prediction.py`: The main Python script implementing the end-to-end pipeline.
* Dataset: Assumes the file `diabetes.csv` is available in the working directory.

## 📊 Dataset

The dataset used is the **PIMA Indians Diabetes Database**, which contains the following medical parameters:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age
* Outcome (0: Non-Diabetic, 1: Diabetic)

## 🛠️ Features

* Data loading and exploration
* Feature scaling using `StandardScaler`
* Train-test splitting (80-20 split)
* Model training using SVM (linear kernel)
* Accuracy evaluation on both training and testing sets
* Prediction system for new user input

## 🔍 Dependencies

Install the following Python libraries before running the script:

```bash
pip install numpy pandas scikit-learn
```

## 🚀 How to Run

1. Make sure you have the `diabetes.csv` dataset in your working directory.
2. Run the Python script:

```bash
python project_3_diabetes_prediction.py
```

3. The script will:

   * Display dataset insights
   * Train an SVM model
   * Show accuracy results
   * Predict diabetes status for a sample input

## 📈 Sample Output

```
Accuracy score of the training data : 0.78
Accuracy score of the test data : 0.77
The person is diabetic
```

## 📌 Notes

* The input for prediction can be modified by changing the `input_data` tuple in the script.
* You can experiment with other models like Decision Trees, Random Forests, or Logistic Regression for comparison.

---

Would you like me to include a sample `diabetes.csv` file structure or usage example in the README?
