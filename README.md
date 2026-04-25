<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00C2FF&center=true&vCenter=true&width=900&lines=AI-Based+Web+Application+Security+System;CNN+%2B+LSTM+Threat+Detection;Explainable+AI+(SHAP)+Integration;SQLi+%7C+XSS+%7C+Zero-Day+Attack+Detection" />
</p>

<h3 align="center">🚀 Intelligent Web Security using Deep Learning</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge&logo=pytorch" />
  <img src="https://img.shields.io/badge/Status-Research%20Stage-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Security-AI%20WAF-green?style=for-the-badge" />
</p>

---

## 📌 Abstract
This project proposes an AI-enhanced Web Application Firewall (WAF) designed to detect and mitigate modern web application threats such as SQL Injection (SQLi), Cross-Site Scripting (XSS), and zero-day attacks.

Traditional security systems rely on static signature-based detection methods, which are ineffective against rapidly evolving and obfuscated attack patterns.

To address this limitation, this research implements a deep learning-based hybrid architecture combining Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) for intelligent threat detection.

The system is trained using the SR-BH 2020 multi-label dataset from IEEE DataPort, which contains real-world HTTP traffic labeled according to CAPEC attack patterns.

To handle class imbalance, the dataset is improved using **SMOTE (Synthetic Minority Over-sampling Technique)**.

Additionally, **Explainable AI (SHAP)** is used to interpret model decisions and improve trust.

---

To enhance performance:

* ⚖️ **SMOTE** is used to handle class imbalance
* 🔍 **SHAP (Explainable AI)** is integrated for interpretability

---

## 🎯 Objectives

* 🧠 Develop a **CNN-LSTM intrusion detection model**
* 🎯 Achieve high detection accuracy
* ⚖️ Balance dataset using **SMOTE**
* 🔍 Provide explainable outputs using **SHAP**
* ⚡ Enable real-time detection (< 60 ms latency)

---

## 📊 Dataset

| Feature    | Description                    |
| ---------- | ------------------------------ |
| 📁 Name    | SR-BH 2020 Multi-label Dataset |
| 🌐 Source  | IEEE DataPort                  |
| 🏷️ Labels | CAPEC Attack Classification    |
| 📡 Type    | Real-world HTTP Traffic        |

---

## 🧠 System Architecture

```text
[ HTTP Traffic ]
        ↓
[ Preprocessing ]
(Tokenization + Normalization)
        ↓
[ CNN + LSTM Model ]
        ↓
[ SHAP Explainability Layer ]
        ↓
[ Threat Detection Output ]
```
## 🧠 System Architecture Overview

<p align="center">
  <img src="images/Architecture.png" width="950"/>
</p>

<p align="center" style="font-size:14px;">
Figure 1: Proposed CNN-LSTM based Web Application Security Architecture with Explainable AI Layer
</p>
---

## 🛠️ Tools & Technologies

### 💻 Programming & Machine Learning

* Python 3.x
* PyTorch
* Scikit-learn
* NumPy
* Pandas

### 🔐 Security & Analysis

* Burp Suite
* SHAP (Explainable AI)

### 📊 Dataset Source

* IEEE DataPort (SR-BH 2020)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Abayshemelis/ResearchProposalPaper.git
cd ResearchProposalPaper
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

---

## 📈 Evaluation Metrics

* ✅ Accuracy
* 🎯 Precision
* 🔁 Recall
* ⚖️ F1-Score
* ⚡ Detection Latency (< 60 ms)

---

## 🔐 Ethical Considerations

* ✔ GDPR-compliant data handling
* ✔ No personal data exposure
* ✔ Dataset anonymization applied
* ✔ Bias monitoring in AI predictions

---

## 📚 References

* IEEE DataPort — SR-BH 2020 Dataset
* CIC-IDS2017 Dataset
* Ammar & Alharbi (2025)
* Thalji et al. (2023)

---

## 👨‍💻 Author

**Abay Shemelis**
🎓 Hawassa University — Computer Science

---

## ⭐ Project Status

🚧 *Research Proposal Stage — Model Development in Progress*

---

## 💡 Future Improvements

* Real-time deployment with proxy integration
* Transformer-based models (BERT, GPT variants)
* Adaptive threat intelligence system
* Web dashboard for monitoring attacks

---
