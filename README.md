# 🧠 Employee Salary Prediction using Machine Learning

Welcome to the **Employee Salary Prediction** project!  
This machine learning model predicts whether an employee's salary is **above or below $50K** annually, based on their personal and professional attributes.

---

## 📌 Project Highlights

- 🔍 **Data Source**: UCI Adult Income Dataset  
- ⚙️ **Model Type**: Supervised Classification  
- 📈 **Algorithms**: Logistic Regression, Random Forest, Gradient Boosting, SVM, KNN  
- 🌐 **Deployment Option**: Streamlit / Flask  
- 🧩 **Output**: Predicts if salary is `>50K` or `<=50K`

---

## 🗂️ Folder Structure

```

├── data/                  # Raw dataset
├── notebooks/             # EDA & model building notebooks
├── requirements.txt
└── README.md

````

---

## 🧰 Technologies Used

| Tool/Library | Purpose                          |
|--------------|----------------------------------|
| Python       | Programming Language             |
| Pandas       | Data Manipulation                |
| NumPy        | Numerical Computation            |
| Scikit-learn | ML Algorithms & Preprocessing    |
| Matplotlib   | Data Visualization               |
| Joblib       | Model Serialization              |
| Streamlit    | Web App Deployment (Optional)    |

---

## 📊 Features Used

- Age  
- Education Level  
- Occupation  
- Hours per Week  
- Work Experience  
- Native Country  
- Marital Status  
- Salary Label (`>50K` or `<=50K`)

---

## 🚀 How to Run the Project

1. **Clone the repository**  
   ```bash
   git clone https://github.com/MouryaSagar17/Employee-Salary-Prediction.git
   cd Employee-Salary-Prediction
    ```

2. **Install the dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model**

   ```bash
   python src/train_model.py
   ```

4. **Launch the Streamlit app (Optional)**

   ```bash
   streamlit run app.py
   ```

---

## 📈 Model Performance

* ✅ Accuracy: **85%+** (varies by algorithm)
* 📉 Precision, Recall, F1-score: Reported in terminal output
* 📊 Confusion Matrix & Feature Importance: Visualized in notebook

---
## 📊 Accuracy Predictions
![Predicting the Highest Accuracy](img/Accuarcy_Preditctions.png)

## 📈 Model Comparisons
![Model Comparisons](img/Model_Comparisons.png)

## 📱 App Running Screenshot
![App Running](img/App_Running.png)

## 🧾 Sample Output 1
![Sample Output 1](img/Sample_Output1.png)

## 🧾 Sample Output 2
![Sample Output 2](img/Sample_Output2.png)

## 🔍 Example Prediction

| Feature        | Value        |
| -------------- | ------------ |
| Age            | 34           |
| Education      | Bachelors    |
| Occupation     | Tech-support |
| Hours/Week     | 40           |
| Experience     | 5            |
| **Prediction** | 💰 `<=50K`   |

---

## 🧠 Future Improvements

* 📦 Add advanced models like XGBoost or LightGBM
* 🧮 Include regression mode to predict actual salary amount
* 🌍 Add country-wise salary normalization
* 🧾 Improve explainability using SHAP / LIME

---

## 📚 References

* 📊 [UCI Machine Learning Repository – Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
* 📘 [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
* 📕 Géron, A. (2019). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*
* 💬 [Kaggle Discussions](https://www.kaggle.com/uciml/adult-census-income)

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome!
Please open an issue or submit a pull request.

---


