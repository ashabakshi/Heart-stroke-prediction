# ❤️ Heart Stroke Prediction App

> An end-to-end Machine Learning project that predicts the risk of heart stroke based on patient health parameters.  
> Trained a KNN classification model, saved with joblib, and deployed as a live web app using Streamlit.

<p>
  <a href="https://heart-stroke-prediction-ashabakshi.streamlit.app/">
    <img src="https://img.shields.io/badge/🚀 Live App-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Live App"/>
  </a>
</p>

---

## 📌 Project Overview

| Detail | Info |
|--------|------|
| **Type** | End-to-End ML Project with Deployment |
| **Domain** | Healthcare / Medical Risk Prediction |
| **Algorithm** | K-Nearest Neighbors (KNN) |
| **Dataset** | `heart.csv` — patient health records |
| **Deployment** | Streamlit Cloud |
| **Live App** | [heart-stroke-prediction-ashabakshi.streamlit.app](https://heart-stroke-prediction-ashabakshi.streamlit.app/) |

---

## 🎯 Objective

Build a real-time prediction app that takes patient health inputs and predicts whether the person is at risk of a heart stroke — making ML useful and accessible through a simple web interface.

---

## 🗂️ Repository Structure

```
Heart-stroke-prediction/
│
├── HeartDisease.ipynb       ← EDA + Model training notebook
├── app.py                   ← Streamlit web app
├── heart.csv                ← Dataset
├── KNN_heart_model.pkl      ← Trained KNN model (saved)
├── heart_scaler.pkl         ← Fitted StandardScaler (saved)
├── heart_columns.pkl        ← Feature column names (saved)
└── requirements.txt         ← Dependencies for deployment
```

---

## ⚙️ ML Pipeline

1. **Data Loading** — Load `heart.csv` using Pandas
2. **EDA** — Explore distributions, correlations, class balance
3. **Preprocessing** — Handle missing values, encode categoricals, scale features
4. **Model Training** — Train KNN classifier using Scikit-learn
5. **Model Evaluation** — Accuracy, Confusion Matrix, Classification Report
6. **Model Saving** — Save model, scaler & columns using `joblib`
7. **Deployment** — Build Streamlit app & deploy on Streamlit Cloud

---

## 🚀 Features

- ✅ Real-time heart stroke risk prediction
- ✅ Clean, user-friendly Streamlit interface
- ✅ Pre-trained KNN model with StandardScaler
- ✅ Fully deployed — accessible from any browser
- ✅ Input validation and instant results

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas & NumPy | Data processing |
| Scikit-learn | KNN model + preprocessing |
| Joblib | Model serialization (.pkl) |
| Matplotlib & Seaborn | EDA visualizations |
| Streamlit | Web app framework |
| Streamlit Cloud | Deployment |
| Jupyter Notebook | Model training & EDA |

---

## 💻 Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/ashabakshi/Heart-stroke-prediction.git
cd Heart-stroke-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run app.py
```

---

## 💡 What I Learned

- Full ML workflow from raw data to deployed app
- Data preprocessing — encoding, scaling, handling imbalance
- KNN algorithm — how distance-based classification works
- Saving and loading ML models using joblib (`.pkl` files)
- Building interactive UIs with Streamlit
- Deploying ML apps on Streamlit Cloud

---

## 👩‍💻 About

**Asha Bakshi** — Aspiring Data Scientist | BCA 3rd Year  
Building end-to-end ML projects with real-world deployment experience.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/asha-bakshi-7227542a2)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ashabakshi)
[![Live App](https://img.shields.io/badge/Live%20App-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://heart-stroke-prediction-ashabakshi.streamlit.app/)
