# 💸 DoomSpend — AI-Powered Expense Intelligence Dashboard

<p align="center">
Turning messy transactions into clear financial decisions.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ML-Naive%20Bayes-blue" />
  <img src="https://img.shields.io/badge/NLP-TF--IDF-orange" />
  <img src="https://img.shields.io/badge/Framework-Streamlit-red" />
  <img src="https://img.shields.io/badge/Accuracy-85%25-brightgreen" />
  <img src="https://img.shields.io/badge/Status-Deployed-success" />
</p>

---

## 🚀 Live Demo

👉 https://doomspend.streamlit.app/

---

## 🎯 Why This Project Exists

Tracking expenses sounds simple — until real life happens.

Transactions like:

* *“zomato order”*
* *“uber ride”*
* *“gpay to friend”*

…are messy, inconsistent, and hard to analyze.

### ➡️ Result:

* No clarity
* No patterns
* No control over money

**DoomSpend solves this by converting raw transaction text into meaningful financial insights.**

---

## 🧠 What It Does

DoomSpend is an **end-to-end ML-powered financial intelligence system** that:

✔ Understands raw transaction text
✔ Automatically classifies expenses
✔ Visualizes spending behavior
✔ Detects anomalies
✔ Suggests savings opportunities

---

## ✨ Features

| Feature                  | Description                           |
| ------------------------ | ------------------------------------- |
| 🧠 NLP Classification    | Predicts category from text input     |
| 📊 Interactive Dashboard | Real-time financial insights          |
| 📈 Trend Analysis        | 7-day moving average visualization    |
| ⚠️ Anomaly Detection     | Flags unusual transactions            |
| 💡 AI Recommendations    | Suggests savings improvements (~₹98K) |
| 💰 Cash Flow Analysis    | Income vs Spending visualization      |

---

## 🧩 System Architecture

```
User Input
   ↓
Text Cleaning & Normalization
   ↓
TF-IDF Vectorization (Bigrams)
   ↓
Naive Bayes Model
   ↓
Prediction
   ↓
Streamlit Dashboard
   ↓
Insights + Anomaly Detection + Recommendations
```

---

## 📸 Screenshots

### 📊 Dashboard Overview

![Dashboard](assets/dashboard.png)

### 📈 Spending Distribution

![Distribution](assets/distribution.png)

### 💰 Cash Flow Health

![Cash Flow](assets/cashflow.png)

> *(Create an `assets/` folder and add your screenshots here)*

---

## 📊 Dataset

* 1000+ transactions

* Simulates real student financial behavior

* Categories:

  * Food 🍔
  * Travel 🚗
  * Bills 💡
  * Shopping 🛍️
  * Entertainment 🎬
  * Income 💰

* 📅 Time Range: **Jan – May 2026**

* Includes noise, ambiguity, and real-world inconsistencies

---

## 🧪 Model & Approach

### 🔹 Feature Engineering

* TF-IDF with **bigrams**
* Captures contextual meaning:

  * *“uber ride” ≠ “uber eats”*

---

### 🔹 Model

**Multinomial Naive Bayes**

* Optimized for text classification
* Efficient on sparse data
* Fast and scalable

👉 Also evaluated **Logistic Regression** as a baseline

---

## 📈 Results

* 🎯 **Accuracy:** ~85%
* 📊 Balanced performance across categories
* 🧠 Handles noisy real-world inputs effectively

---

## 🧠 Key Insights

* Travel & entertainment → highest spending drivers
* Food → frequent but low-value transactions
* Income → sparse but high-value

💡 **Potential savings improvement:** ~₹98K

---

## ⚠️ Anomaly Detection

* Flags transactions **> 1.8× category average**
* Based on **rolling 30-day behavior**

---

## 💻 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Streamlit

---

## ⚡ Run Locally

```bash
git clone https://github.com/your-username/DoomSpend.git
cd DoomSpend
pip install -r requirements.txt
streamlit run app.py
```

---

## 🚧 Limitations

* Synthetic dataset
* Limited vocabulary scope
* No real banking integration

---

## 🔮 Future Improvements

* BERT / Deep Learning models
* Real-time transaction ingestion
* Mobile/Web deployment
* Personalized financial AI

---

## 🏁 Final Thought

DoomSpend goes beyond expense tracking —
it transforms financial data into **decision-making intelligence**.

---

## 👩‍💻 Author

**Riya Shah**
B.Tech Computer Engineering

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!
