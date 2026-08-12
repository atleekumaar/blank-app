#  Rock vs Mine Prediction App 

An end-to-end Machine Learning web application that predicts whether an object detected by Sonar data is a **Rock** or a **Submarine Mine**. Built with Python, Scikit-learn, and Streamlit.

---

## 📌 Overview

Sonar (Sound Navigation and Ranging) technology sends sound waves to detect objects under water. This application uses a binary classification machine learning model to analyze sonar return signals at various angles and predict whether the obstacle is a harmless rock or a dangerous naval mine.

### Features
* **Interactive Web Interface:** User-friendly UI built with Streamlit.
* **Real-time Prediction:** Enter sonar sensor data to get instant classification.
* **Supervised Machine Learning:** Powered by a Logistic Regression classification model.
* **High Accuracy:** Trained and evaluated on standard Sonar dataset metrics.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.8+
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy
* **Web Framework:** Streamlit
* **Deployment:** GitHub / Streamlit Community Cloud

---

## 📁 Project Structure

```text
Rock-vs-mine-pred.app/
├── README.md               # Documentation and execution guide
├── app.py                  # Streamlit web application code
├── rock_vs_mine_model.pkl  # Trained ML model artifact
├── Copy of sonar data.csv  # Sonar dataset used for training
└── requirements.txt        # Python dependencies
```
## 📊 Dataset & Model Information

* **Dataset:** Sonar, Mines vs. Rocks Dataset (60 input numerical features representing sonar signal frequencies).
* **Target Classes:** 
  * `R` -> Rock
  * `M` -> Mine
* **Model Used:** Logistic Regression.
