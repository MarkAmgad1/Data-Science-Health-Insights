# 📊 Data Science Health Insights

A full data science pipeline built to assess patient health risks using the **Framingham dataset**.  
The project includes **data preprocessing**, **outlier detection**, multiple **imputation techniques**, **classification models**, and a final **Power BI dashboard** to visualize key insights.

---

## 📁 Project Structure

```
Data-Science-Health-Insights/
├── final.ipynb              # Jupyter Notebook: full data science workflow
├── framingham.csv            # Original dataset
├── dashboard.pbix            # Power BI dashboard file (not uploaded here)
└── README.md                 # This file
```

---

## 🚀 Key Features

- Preprocessing with:
  - Missing value imputation (Mean, Median, Mode, KNN, MICE, Autoencoder)
  - Outlier detection (Z-score, IQR, Isolation Forest, DBSCAN)
- Classification using:
  - Logistic Regression
  - Random Forest
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score
- Export-ready dataset for Power BI
- Interactive **Power BI dashboard** for health insights

---

## 📌 Dataset

- **Source**: Framingham Heart Study
- **Records**: 4,240+
- **Features**: Age, Gender, Blood Pressure, Smoking, Diabetes, etc.
- **Target**: 10-year risk of coronary heart disease (CHD)

---

## 🧠 Tools Used

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- TensorFlow (for autoencoder)
- Power BI (for dashboard)

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).
