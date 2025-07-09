# 🎯 Student Performance Prediction - ML

A beginner-friendly Machine Learning project to predict student performance (pass/fail) using academic and demographic data. Built in Python with scikit-learn and designed for quick execution on Google Colab.

---

## 📌 Features

✅ Load and preprocess student data from CSV  
✅ Visualize data distributions and correlations (Matplotlib & Seaborn)  
✅ Train/test split for model validation  
✅ Build and compare multiple ML models:
- Logistic Regression
- Decision Tree
- Random Forest
✅ Evaluate models using:
- Accuracy
- Confusion Matrix
- Classification Report
✅ Plot feature importance for better interpretability

---

## ☁️ Run on Google Colab

Skip local setup and run this project directly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pp3TyDoWrv21wqvIGDzPlODKHyct5mBR#scrollTo=vDQb4n4NPZxi)

1. Click the **“Open in Colab”** badge above.  
2. Upload your dataset (`AI-Data.csv`) when prompted.  
3. Run all cells in the notebook.

---

## 🗄️ Dataset

The project uses a CSV file (`AI-Data.csv`) containing student performance data. You can:
- Upload your dataset to Colab when running.
- Or use the sample dataset provided in this repository.

---

## 🚀 Getting Started (Optional Local Setup)

### 📦 Prerequisites
Install Python 3.x and pip.

## 🖥️ Project Structure
│
├── Project.py # Main Python script\n
├── AI-Data.csv # Dataset file (place here)\n
├── requirements.txt # Python dependencies\n
├── README.md # Project documentation\n
└── StudentPP.ipynb


## 🌟 Future Improvements
- Add hyperparameter tuning (GridSearchCV)
- Deploy as a Streamlit web app
- Integrate other datasets for multi-class prediction

---

### 🔥 Installation
```bash
git clone https://github.com/yourusername/StudentPerformancePrediction-ML.git
cd StudentPerformancePrediction-ML
pip install -r requirements.txt
python Project.py

---

## 📊 Example Outputs

| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression| 85%      |
| Decision Tree      | 82%      |
| Random Forest      | 88%      |

---
