# Predict Diabetes with Machine Learning

This project predicts whether a person is diabetic based on health metrics using **Machine Learning** models.

##  Features
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature scaling and encoding  
- Training with algorithms like Logistic Regression, Random Forest, and SVM  
- Model performance evaluation (accuracy, precision, recall, F1-score)

##  Files
- `Predict_Diabetes_with_Machine_Learning.ipynb` → Main Jupyter Notebook  
- `README.md` → Project documentation  

## Requirements
Install dependencies:
```bash```
pip install numpy pandas scikit-learn matplotlib seaborn

##  Dataset
The dataset used in this project is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

It contains medical information such as:
- **Pregnancies**
- **Glucose**
- **Blood Pressure**
- **Skin Thickness**
- **Insulin**
- **BMI**
- **DiabetesPedigreeFunction**
- **Age**
- **Outcome** (1 = Diabetic, 0 = Not Diabetic)

Make sure to download the dataset and place it in your working directory before running the notebook.

---

##  Model Summary
The model analyzes health parameters to predict whether a patient is likely to have diabetes.  
It uses supervised learning techniques like:
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)

Performance is evaluated using metrics such as:
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

##  Results
The trained models were compared, and the one with the **highest accuracy and balanced performance** was selected.  
Visualization graphs and confusion matrices are available within the notebook.

---

##  How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Predict_Diabetes_with_Machine_Learning.ipynb"

