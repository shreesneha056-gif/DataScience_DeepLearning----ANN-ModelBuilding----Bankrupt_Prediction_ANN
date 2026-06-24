# 🏦 Corporate Bankruptcy Prediction using ANN

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-96%25-brightgreen?style=flat-square)

> End-to-end deep learning pipeline to predict corporate bankruptcy from financial indicators using an Artificial Neural Network (ANN).

---

## 📌 Problem Statement
Predicting corporate financial distress early is critical for banks, investors, and regulators. This project builds a binary classification model that flags companies likely to go bankrupt based on historical financial metrics.

## 🎯 Results
| Metric | Score |
|--------|-------|
| Accuracy | **96%** |
| Model | Sequential ANN (Keras) |
| Task | Binary Classification |

## 🛠️ Tech Stack
- **Language:** Python
- **Deep Learning:** Keras, TensorFlow
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📂 Project Structure
```
bankruptcy-prediction-ann/
├── Bankrupt_Prediction_ANN/
│   ├── data/          # Raw and processed datasets
│   ├── python/        # Jupyter notebooks & scripts
│   └── README.md
└── README.md
```

## 🚀 How to Run
```bash
# 1. Clone the repo
git clone https://github.com/shreesneha056-gif/bankruptcy-prediction-ann.git
cd bankruptcy-prediction-ann

# 2. Install dependencies
pip install tensorflow keras pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Launch Jupyter
jupyter notebook
```
Then open the notebook inside the `python/` folder.

## 📊 Pipeline Overview
1. **Data Loading & EDA** — Explore financial indicators
2. **Preprocessing** — Handle missing values, scale features
3. **Model Building** — Sequential ANN with Dense + Dropout layers
4. **Training & Evaluation** — Accuracy, confusion matrix, classification report
5. **Results** — 96% classification accuracy

---
📫 [Connect on LinkedIn](https://www.linkedin.com/in/sneha-shree-mu/) | [Portfolio](https://shreesneha056-gif.github.io/portfolio_website/)
