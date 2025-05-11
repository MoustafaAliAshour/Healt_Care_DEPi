
# Heart Disease Treatment Prediction using Machine Learning

This project is developed under the **Digital Egypt Pioneers Initiative (DEPI)** as a practical application of the Data Science curriculum. The main goal is to predict the most suitable treatment for heart disease patients based on clinical and demographic data using machine learning models.

🔗 **GitHub Repository**: [github.com/rezk1834/DEPI](https://github.com/rezk1834/DEPI)

---

## 🚀 Objective

To predict patient treatment plans using a machine learning pipeline trained on a synthetic health dataset. The target treatments include:
- **Medication**
- **Lifestyle Changes**
- **Angioplasty**
- **Coronary Artery Bypass Graft (CABG)**

---

## 🧠 Technologies & Libraries

- **Python 3**
- **Pandas, NumPy** – Data manipulation
- **Scikit-learn** – ML models & evaluation
- **Matplotlib, Seaborn** – Visualizations
- **Streamlit** – Web application deployment

---

## 📊 Dataset Overview

- **Total Records**: 1,000
- **Features**:
  - Gender
  - Age
  - Blood Pressure (mmHg)
  - Cholesterol (mg/dL)
  - Has Diabetes
  - Smoking Status
  - Chest Pain Type
  - Treatment (Target)

### Data Quality
- No null values
- Types: 3 numeric, 5 categorical
- Cleaned and encoded before modeling

---

## ⚙️ Methodology

1. **Preprocessing**
   - Label Encoding for categorical features
   - Train-test split (80-20)

2. **Modeling**
   - Random Forest, Decision Tree, Logistic Regression tested
   - GridSearchCV used for hyperparameter tuning

3. **Evaluation**
   - Accuracy: **~26%**
   - Precision/Recall analysis via Classification Report
   - Confusion Matrix & Feature Importance
   - ROC Curve for multiclass analysis

4. **Best Model**
   - **Random Forest Classifier**
   - Parameters: `{'max_depth': 10, 'min_samples_split': 5, 'n_estimators': 100}`

---

## 🌐 Deployment

The model was deployed using **Streamlit**, allowing real-time input and prediction for end users.

### How to Run:
```bash
git clone https://github.com/rezk1834/DEPI
cd DEPI
pip install -r requirements.txt
streamlit run app.py
````

---

## 📁 Project Structure

```
DEPI/
├── data/
│   └── health.csv
├── models/
│   └── best_model.pkl
├── app.py
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 🧩 Results & Discussion

While the accuracy was moderate due to overlapping features and treatment complexity, the pipeline effectively:

* Encapsulates key ML processes
* Demonstrates feature importance
* Shows clear visual outputs and model diagnostics
* Provides a functional web-based interface

---

## ✅ Conclusion

This project illustrates a complete ML lifecycle: from data cleaning and modeling to deployment. Developed as part of the **DEPI Data Science Track**, it highlights the capability to solve real-world healthcare prediction problems using data-driven methods.

Further improvements could include:

* Feature engineering
* Larger and more diverse datasets
* Using deep learning or ensemble stacking

---

### 👨‍💻 Author

**Moustafa Rezk**
DEPI – Data Science Track
GitHub: [rezk1834](https://github.com/rezk1834)

