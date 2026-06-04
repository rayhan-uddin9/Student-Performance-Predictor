# 🎓 Student Performance Predictor

> A Machine Learning model that predicts whether a student will **pass or fail** based on study habits, attendance and previous scores — built with Python, Scikit-Learn and Seaborn.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![ML](https://img.shields.io/badge/ML-Logistic_Regression-9cf)

---

## 📌 About this project

Every year thousands of students struggle academically without early warning. This project builds a Machine Learning model that can predict a student's result early — giving teachers and institutions a chance to help before it is too late.

I built this project to apply **Logistic Regression** to a real education problem, inspired by my own experience as a Computer Science student.

---

## 🎯 Problem Statement

```
Given:
  → Daily study hours
  → Attendance percentage
  → Previous exam score

Predict:
  → Will the student PASS or FAIL?
```

---

## 🗂️ Dataset

I created a realistic dataset of 30 students with the following features:

| Feature | Type | Description |
|---------|------|-------------|
| `study_hours` | int | Hours studied per day |
| `attendance_pct` | int | Attendance percentage (0–100) |
| `prev_score` | int | Previous exam score (0–100) |
| `passed` | int | 1 = Passed, 0 = Failed |

---

## 🔄 Project Workflow

```
Create Dataset
      ↓
Explore and Understand Data
      ↓
Visualize with Charts
      ↓
Split Train and Test (80/20)
      ↓
Train Logistic Regression Model
      ↓
Evaluate with Accuracy and Confusion Matrix
      ↓
Predict New Student Results
```

---

## 📊 Model Results

| Metric | Result |
|--------|--------|
| Algorithm | Logistic Regression |
| Accuracy | ~100% on test set |
| Train/Test Split | 80% / 20% |

---

## 🖼️ Visualizations included

- 📉 Study Hours vs Previous Score — colored by Pass/Fail
- 📊 Attendance Distribution — Pass vs Fail comparison
- 📈 Pass vs Fail bar chart
- 🔥 Confusion Matrix heatmap

---

## 💡 Sample predictions

```python
# Student who studies well
predict_student(study_hours=6, attendance=85, prev_score=70)
# Pass Probability : 95.3%
# Result : ✅ PASS

# Student who does not study
predict_student(study_hours=1, attendance=45, prev_score=35)
# Pass Probability : 4.1%
# Result : ❌ FAIL
```

---

## 🛠️ Tech stack

| Tool | Purpose |
|------|---------|
| Python | Programming language |
| NumPy | Numerical computation |
| Pandas | Data handling |
| Matplotlib | Charts |
| Seaborn | Heatmap visualization |
| Scikit-Learn | ML model training and evaluation |
| Jupyter Notebook | Development environment |

---

## 🚀 How to run

**On Google Colab — no installation needed**
1. Open the `.ipynb` file in this repository
2. Click **Open in Colab**
3. Click **Runtime → Run all**

**On local machine**
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook Student_Performance_Predictor.ipynb
```

---

## 📁 Repository structure

```
Student-Performance-Predictor/
├── Student_Performance_Predictor.ipynb   # main notebook
└── README.md                             # project documentation
```

---

## 🔮 What I plan to add next

- [ ] Use a real dataset from Kaggle with 1000+ students
- [ ] Add more features — sleep hours, part time job, internet access
- [ ] Compare with Decision Tree and Random Forest models
- [ ] Build a simple web app using Flask or Streamlit
- [ ] Send early warning alert to teacher if student is at risk

---

## 🧠 What I learned

This project taught me how Logistic Regression works for classification problems. Unlike Linear Regression which predicts numbers, Logistic Regression predicts categories — pass or fail, yes or no. I also learned how to read a Confusion Matrix and understand precision and recall, which are important for evaluating real world ML models.

---

## 🔗 Related repositories

- 📂 [ML-Practice](https://github.com/rayhan-uddin9/ML-Practice) — ML learning and practice notebooks
- 📂 [House-Price-Prediction](https://github.com/rayhan-uddin9/House-Price-Prediction) — Linear Regression project
- 📂 [Python-Documentation](https://github.com/rayhan-uddin9/Python-Documentation) — 30-class Python training course

---

> 🎓 **Rayhan Uddin** · Computer Science Student · Bangladesh
>
> *"Education data is powerful. If we can predict who needs help, we can help them before it is too late."*
