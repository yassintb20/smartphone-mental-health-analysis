# 🧠 Smartphone Mental Health Analysis

> Machine learning analysis of smartphone behavioral data to detect patterns associated with mental well-being variations.

---

## 📌 Overview

This project investigates the relationship between smartphone usage patterns and mental health indicators. Through exploratory data analysis and multiple ML models, it identifies behavioral signals that correlate with mental state variations.

---

## 🔬 Research Question

> *Can smartphone behavioral data (screen time, app usage, notifications, etc.) predict mental well-being indicators?*

---

## 📊 Methodology

```
Raw Data (Smartphone Behavioral Metrics)
         │
         ▼
┌─────────────────────┐
│  EDA & Visualization│  ← Distribution, correlations, outliers
└──────────┬──────────┘
           │
┌──────────▼──────────┐
│ Feature Engineering │  ← Selection, encoding, scaling
└──────────┬──────────┘
           │
┌──────────▼──────────┐
│   Model Training    │  ← Multiple algorithms compared
│  • Logistic Reg.    │
│  • Random Forest    │
│  • SVM              │
│  • KNN              │
│  • XGBoost          │
└──────────┬──────────┘
           │
┌──────────▼──────────┐
│ Evaluation & Report │  ← Accuracy, F1, confusion matrix
└─────────────────────┘
```

---

## 📈 Key Findings

- Identified top behavioral features most correlated with mental well-being
- Compared performance of 5+ supervised ML models
- Applied feature selection to reduce dimensionality
- Evaluated using cross-validation to ensure generalization

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **ML**: Scikit-learn, XGBoost
- **Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yassintb20/smartphone-mental-health-analysis.git
cd smartphone-mental-health-analysis

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook analysis.ipynb
```

---

## 📁 Project Structure

```
smartphone-mental-health-analysis/
├── data/
│   └── smartphone_data.csv    # Dataset
├── notebooks/
│   ├── 01_EDA.ipynb           # Exploratory analysis
│   ├── 02_preprocessing.ipynb # Feature engineering
│   └── 03_modeling.ipynb      # Model training & evaluation
├── src/
│   ├── preprocessing.py
│   └── models.py
├── results/
│   └── model_comparison.png   # Performance comparison chart
├── requirements.txt
└── README.md
```

---

## 👤 Author

**Taibi Mohamed Yassine** — [LinkedIn](https://linkedin.com/in/mohammed-yassin-taibi) · [GitHub](https://github.com/yassintb20)
