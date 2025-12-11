# 🔊 Sonar Rock vs Mine Prediction

A Machine Learning project that uses the **Sonar Dataset** to classify whether an object detected by sonar is a **Rock (R)** or a **Mine (M)**.
This project uses **Logistic Regression** and evaluates accuracy on both training and test data.

---

## 📌 Project Overview

Sonar signals are reflected differently by rocks and metal mines.
This project trains a machine learning model using those sonar frequency features (60 features per instance) to classify the detected object.

The dataset used is the **Sonar Mines vs Rocks dataset** from UCI Machine Learning Repository.

---

## 📂 Features of the Project

* Data loading and processing using **Pandas & NumPy**
* Train-test split using **Scikit-learn**
* Logistic Regression classification
* Accuracy evaluation
* Manual input prediction for new sonar data

---

## 🧠 Technologies Used

* Python
* NumPy
* Pandas
* Scikit‑learn

---

## 📁 Dataset

The dataset contains:

* **208 samples**
* **60 numerical features** (sonar frequencies)
* **1 target column** (R = Rock, M = Mine)

---

## 🚀 How to Run the Project

1. Install required libraries:

```bash
pip install numpy pandas scikit-learn
```

2. Place the dataset (CSV file) in your project directory.
3. Update the CSV path in the script:

```python
sonar_data = pd.read_csv('sonar_data.csv', header=None)
```

4. Run the Python file:

```bash
python rock_vs_mine_data_prediction.py
```

---

## 📊 Model Performance

* The model is trained using **Logistic Regression**.
* It prints:

  * Training Accuracy
  * Test Accuracy
  * Prediction for a custom input sample

---

## 🔍 Sample Prediction Output

```
['R']
The object is a Rock
```

---

## 📦 File Structure

```
├── rock_vs_mine_data_prediction.py
├── sonar_data.csv
└── README.md
```

---

## ✨ Future Enhancements

* Try alternative ML models (Random Forest, SVM, KNN)
* Build a web interface using Flask/Streamlit
* Add model saving using Pickle
* Visualize feature importance

---

## 🧑‍💻 Author

Akash Rao
---

If you found this helpful, ⭐ the repository!
