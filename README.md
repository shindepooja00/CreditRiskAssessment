# 📌 Credit Risk Assessment

## 📖 Introduction
This repository contains a **Credit Risk Assessment System** designed to predict loan default probabilities and categorize borrowers into different risk levels using **Bank's Finance’s dataset**.

## 🚀 Features
- **Predictive Model**: Utilizes historical loan data and default indicators to assess credit risk.
- **Credit Scorecard**: Classifies credit scores into **Poor, Average, Good, and Excellent** categories.
- **Streamlit UI**: Interactive interface for loan officers to input borrower details and receive credit risk assessments.
- **Performance Monitoring**: Continuous evaluation of model performance to detect drift.
- **Operational Integration**: Implements **Straight Through Processing (STP)** for high-confidence applications, reducing manual intervention.

## 🛠️ Tech Stack
- **Python** (pandas, scikit-learn, NumPy)
- **Streamlit** (for UI development)
- **MLflow** (for model tracking and performance monitoring)
- **Docker** (for deployment)
- **AWS/GCP/Azure** (for cloud-based MLOps)
- **SQL** (for storing credit risk data)

## 📂 Project Structure
```
📁 credit-risk-assessment
│── 📂 data                # Dataset (historical loan data)
│── 📂 models              # Trained models & scorecard
│── 📂 src                 # Source code for model training & inference
│── 📂 ui                  # Streamlit app code
│── 📜 requirements.txt    # Dependencies
│── 📜 README.md           # Project Documentation
```

## 🚀 Installation & Usage
### 🔧 Prerequisites
- Python (>=3.8)
- Git

### 📥 Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-risk-assessment.git
   cd credit-risk-assessment
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit UI:
   ```bash
   streamlit run ui/app.py
   ```

## 🏆 Contributors
- **[Pooja Shinde]** - Machine Learning Engineer


---
_🚀 Contributions and suggestions are welcome!_
