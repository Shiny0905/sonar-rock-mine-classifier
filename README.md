# 🪨 Rock vs Mine Prediction using SONAR Data

A machine learning project that classifies underwater objects as **rocks** or **mines** using sonar signal data and Logistic Regression.

---

## 📌 Project Overview

This project uses the **SONAR dataset** from the UCI Machine Learning Repository. The dataset contains sonar signals bounced off rocks and metal cylinders (mines) at various angles and under different conditions. The goal is to train a binary classifier to accurately distinguish between the two.

---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository — Connectionist Bench (Sonar, Mines vs. Rocks)
- **Samples:** 208
- **Features:** 60 numerical features representing sonar signal energy across different frequency bands
- **Target:** `R` = Rock, `M` = Mine

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming language |
| NumPy | Array operations |
| Pandas | Data processing |
| Scikit-learn | ML model & evaluation |
| Google Colab | Development environment |

---

## 🧠 Model

- **Algorithm:** Logistic Regression
- **Train/Test Split:** 90% / 10% (stratified)

---

## 📈 Results

| Dataset | Accuracy |
|---------|----------|
| Training | **83.42%** |
| Testing | **76.19%** |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sonar-rock-mine-classifier.git
   ```

2. Open the notebook in Google Colab:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/sonar-rock-mine-classifier/blob/main/RockVsMinePrediction.ipynb)

3. Upload `sonar data.csv` to your Colab environment when prompted.

4. Run all cells.

---

## 📁 Project Structure

```
sonar-rock-mine-classifier/
│
├── RockVsMinePrediction.ipynb   # Main Colab notebook
├── sonar data.csv               # Dataset
└── README.md                    # Project documentation
```

---

## 🔍 What I Learned

- Data preprocessing and exploration using Pandas
- Binary classification using Logistic Regression
- Evaluating model performance with accuracy score
- Working with real-world sonar signal data

---

## 📚 References

- [UCI ML Repository - Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))
- [Scikit-learn Documentation](https://scikit-learn.org/)

---

## 👤 Author

**Your Name**  
[LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/YOUR_USERNAME)
