# Heart-Disease-Classification-Project
This is SLIPD final project in Machine Learning Part
---
title: "❤️‍🔥 Heart Disease Classification - README"
author: "Your Name"
output:
  html_document:
    theme: cosmo
    highlight: haddock
    toc: true
    toc_float: true
---

<style>
body {
  background-color: #f4f6f7;
}
h1 {
  color: #e74c3c;
}
h2 {
  color: #2e86c1;
}
h3 {
  color: #28b463;
}
</style>

# ❤️‍🔥 Heart Disease Classification Project

<p align="center">
<b>🚀 Machine Learning | 📊 Classification | ❤️ Healthcare</b>
</p>

---

## 📌 Project Overview

✨ This project focuses on building a **Machine Learning model** to predict the presence of **heart disease** in patients.

💡 Using patient medical data, the model learns patterns and helps in early diagnosis.

---

## 🎯 Objective

- Predict whether a patient has heart disease  
- Build a reliable classification model  
- Evaluate performance using multiple metrics  

---

## 📊 Dataset Information

### 🔹 Features

| Feature | Description |
|--------|------------|
| 👤 age | Age of patient |
| 🚻 sex | Gender |
| ❤️ cp | Chest pain type |
| 💉 trestbps | Blood pressure |
| 🧪 chol | Cholesterol |
| 🍬 fbs | Blood sugar |
| 📈 thalch | Max heart rate |
| ⚡ exang | Exercise angina |
| 📉 oldpeak | ST depression |
| 🧬 thal | Thalassemia |

### 🎯 Target

- `0` → No Disease  
- `1` → Disease  

---

## ⚙️ Tech Stack

- 🐍 Python / 📊 R  
- 📦 Machine Learning (`glm`, `caret`)  
- 📉 Visualization (`ggplot2`)  
- 📊 Data Processing (`dplyr`)  

---

## 🧠 Model Used

### 🔹 Logistic Regression

✔️ Simple and efficient  
✔️ Works well for classification  
✔️ Easy to interpret  

---

## 🔄 Project Workflow

## 📊 Model Evaluation

### Accuracy Evaluation Graph
![Accuracy Graph](<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/4c0e0706-6b30-4a6e-85e6-cc717e2dc232" />
)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

```mermaid
graph TD
A[📂 Data Collection] --> B[🧹 Data Cleaning]
B --> C[📊 Feature Processing]
C --> D[🤖 Model Training]
D --> E[📈 Evaluation]
E --> F[🎯 Prediction]
