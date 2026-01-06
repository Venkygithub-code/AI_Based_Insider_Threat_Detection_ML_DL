# Insider_Threat_Detection_ML_DL
Insider Threat Detection using ML &amp; DL analyzes employee behavior logs such as login activity, file access, and device usage to detect suspicious actions. It uses a hybrid Isolation Forest and Autoencoder approach to identify anomalies, generate risk scores, and alert security teams with minimal false positives.
Good question 👍

---

# **Insider Threat Detection using Machine Learning & Deep Learning**

## 📌 Project Overview

This project focuses on detecting **insider threats** by analyzing employee behavior patterns such as login times, file access frequency, device usage, and access locations. Since insider attacks often come from authorized users and labeled attack data is limited, the system uses **anomaly detection** with a hybrid **Machine Learning and Deep Learning** approach.

---

## 🎯 Problem Statement

Traditional security systems struggle to detect insider threats because malicious activities often resemble normal behavior. The objective of this project is to build an AI-based system that can identify **suspicious deviations** in employee behavior and raise alerts before serious security incidents occur.

---

## 🧠 Solution Approach

* Preprocess employee activity logs into behavioral features
* Detect global anomalies using **Isolation Forest**
* Detect subtle behavioral changes using a **Deep Learning Autoencoder**
* Combine ML and DL outputs into a unified **risk score**
* Flag activities exceeding a defined threshold as potential threats

---

## 🏗️ System Architecture

```
Employee Activity Logs
        ↓
Data Preprocessing & Feature Engineering
        ↓
Isolation Forest (ML)
        ↓
Autoencoder (DL)
        ↓
Risk Scoring Engine
        ↓
Threat Alert / Normal Status
```

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* TensorFlow / Keras
* Jupyter Notebook

---

## 📊 Output

* Threat status: **Detected / Normal**
* Risk score (0–100)
* Reason for alert (behavioral anomalies)

---


## 👤 Author

**Venkatesh Gudikoti**
AI / ML Enthusiast

---


