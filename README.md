# 📌 Credit Risk Assessment

## 📖 Overview
This project aims to develop a **Credit Risk Assessment System** using **Finance’s dataset** to predict loan default probabilities and categorize borrowers into different risk levels. The solution includes a **predictive model**, a **credit scorecard**, and a **Streamlit UI application** for easy accessibility.

## 🚀 Project Phases

### 🔹 Phase 1: Development and Implementation
1. **Model Development**: Build a predictive model utilizing historical loan data and default indicators.
2. **Scorecard Creation**: Develop a scoring system that categorizes credit scores into **Poor, Average, Good, and Excellent**.
3. **Streamlit UI Application**: Create a user-friendly interface where loan officers can input borrower details (demographics, loan details, credit bureau information) to obtain **default probability predictions** and **credit ratings**.

### 🔹 Phase 2: Monitoring and ML Ops
1. **Performance Monitoring**: Implement monitoring tools to track model performance and detect drift.
2. **Operational Integration**: After a **2-month trial in production**, establish procedures for **Straight Through Processing (STP)** to automate approvals for high-confidence applications, reducing manual intervention.

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
- Install Python (>=3.8)
- Clone this repository:
  ```bash
  git clone https://github.com/your-username/credit-risk-assessment.git
  cd credit-risk-assessment
  ```
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- Run the Streamlit UI:
  ```bash
  streamlit run ui/app.py
  ```

## 🏆 Contributors
- **[Pooja Shinde]** - Machine Learning Engineer

---
_🚀 Feel free to contribute and enhance this project!_
