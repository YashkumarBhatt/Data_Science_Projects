# Data Science Projects

A collection of exploratory data analysis and machine learning projects across different domains — finance, entertainment, cybersecurity, and retail.

Each project folder contains the Jupyter notebook, dataset (CSV), and a project-specific README with objectives, approach, and findings.

---

## Projects

### ☕ [Coffee Sales Analysis & Prediction](./Coffee-Sales-Analysis)
Analyzes 7 months of vending machine coffee sales to uncover trends across coffee types, peak hours, pricing, and payment methods. Includes revenue prediction using Linear Regression and Random Forest models, with feature importance analysis.

`EDA` `Random Forest` `Linear Regression` `Time-Series Features`

---

### 🛡️ [Cybersecurity: Suspicious Web Threat Interactions](./Cybersecurity-Threat-Analysis)
Anomaly detection on Web Application Firewall (WAF) logs using a Deep Learning Autoencoder. Bypasses the data leakage problem of standard classifiers by using unsupervised reconstruction error to isolate the top 10% most critical threats.

`Anomaly Detection` `Autoencoder` `TensorFlow/Keras` `Unsupervised Learning`

---

### 🍿 [Netflix Data Analysis & Visualization](./Netflix-Data-Analysis)
EDA on Netflix's full content catalog — uncovering trends in content type, country of origin, audience ratings, and genre distribution. Includes WordCloud visualizations and temporal trend analysis.

`EDA` `Data Cleaning` `Visualization` `WordCloud`

---

### 📈 [Stock Market Analysis & Prediction](./Stock-Market-Analysis)
Analyzes stock performance of Apple, Google, Microsoft, and Netflix over a 4-month period. Covers price volatility, volume trends, and correlation analysis. Uses a hypertuned Gradient Boosting Regressor to forecast adjusted closing prices.

`EDA` `Gradient Boosting` `RandomizedSearchCV` `Financial Analysis`

---

## Stack

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `Matplotlib` · `Seaborn` · `TensorFlow/Keras` · `WordCloud`

---

## Structure

Each project folder contains:

```
project-name/
├── notebook.ipynb       # Full analysis and modeling
├── data.csv             # Dataset used
└── README.md            # Objectives, approach, and findings
```
