# Lifestyle_Health_Classifier

An intelligent machine learning solution to classify individuals based on their smoking and alcohol consumption habits using health and lifestyle data.

---

## 📌 Objective

This project aims to identify smoking and drinking patterns in individuals based on various health metrics. By leveraging machine learning classification algorithms, we can build a predictive system that can assist in public health research and preventive healthcare initiatives.

---

## 💡 Problem Statement

Given a dataset of individuals with health-related features such as age, BMI, cholesterol levels, etc., predict whether a person is a smoker, drinker, both, or neither. The goal is to help derive insights from healthcare data and build an automated classification pipeline.

---

## 🔍 Technologies & Libraries Used

- **Languages:** Python  
- **Libraries:**  
  - `Pandas`, `NumPy` for data manipulation  
  - `Matplotlib`, `Seaborn` for visualization  
  - `Scikit-learn` for ML models and evaluation

---

## 🧠 ML Models Implemented

- Logistic Regression  
- Random Forest Classifier  
- K-Nearest Neighbors  
- Gaussian Naive Bayes  
- Linear & Quadratic Discriminant Analysis

---

## ⚙️ System Workflow

1. **Data Preprocessing**  
   - Handle missing values  
   - Feature scaling with `StandardScaler`  
   - Categorical encoding if necessary

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots, correlation matrix, and pair plots  
   - Outlier and trend identification

3. **Model Training & Evaluation**  
   - Dataset split into training and test sets  
   - Applied multiple ML classifiers  
   - Evaluated using confusion matrix, accuracy score, classification report

---

## 📈 Output

The system outputs the classification results and provides insights into which health factors most influence smoking and drinking behavior. Comparative results across models are displayed with key metrics.

---

## 🏁 Getting Started

### Prerequisites

Install the necessary packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Notebook
Open Jupyter Notebook and run the cells in class_smoke_alcohol.ipynb step-by-step to view analysis and predictions.

---

## 📂 Dataset
The dataset smoking_driking_dataset.csv should be placed inside the data/ folder. It includes features such as:

- Age
- BMI
- Blood Pressure
- Alcohol Consumption
- Smoking Status
- ... and more

--- 

## 🧪 Results Snapshot
📊 Comparative evaluation of all classifiers shows accuracy and performance metrics for each.
Confusion matrices and reports help visualize misclassifications and performance.

---

## 🤝 Contributing
Feel free to fork this repo and submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

---

## 📫 Contact
Created with ❤️ by Bhavya Parmar
Drop a ⭐ if you like the project!
