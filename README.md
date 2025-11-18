[doctor_recommendation (Task 4).pdf](https://github.com/user-attachments/files/23602478/doctor_recommendation.Task.4.pdf)# **Healthcare Data Analysis & AI Recommendation System**

A complete end-to-end machine learning project including **EDA, supervised learning, anomaly detection, and an AI doctor-style recommendation generator**.
This project demonstrates real-world healthcare data workflows suitable for analytics, ML modeling, and AI-based insights.

---

## 📌 **Project Overview**

This repository contains 4 major tasks:

### **✅ Task 1 — Exploratory Data Analysis (EDA)**

Performed exploratory analysis on the following dataset features:

* Age distribution
* Billing amount distribution
* Room number distribution
* Frequency of:

  * Medical Conditions
  * Admission Types
  * Medications

Includes clean visualizations using **matplotlib**.

🔍 **Files:**

* `Task1_EDA.ipynb`

---
OUTPUT RESULT : 
<img width="1980" height="1180" alt="Age Distribution" src="https://github.com/user-attachments/assets/31bba2b1-a0f0-453b-afbb-b41fdcf20b54" />

<img width="1979" height="1180" alt="Anomaly Detection in Billing Amounts" src="https://github.com/user-attachments/assets/52d020a8-6bf2-4a18-abd3-a02e873694ba" />

<img width="1979" height="1180" alt="Billing Amount Distribution" src="https://github.com/user-attachments/assets/2d4f1718-e410-4a70-a271-172d07c5d4c3" />

<img width="1979" height="1180" alt="Frequency of Admission Types" src="https://github.com/user-attachments/assets/3f3995cd-9e61-4dbc-8abf-0bc851ea8a18" />

<img width="1979" height="1180" alt="Frequency of Medical Conditions" src="https://github.com/user-attachments/assets/354a25ef-6d8a-4880-afd8-b93c1e61d88f" />

<img width="1980" height="1180" alt="Frequency of Medication" src="https://github.com/user-attachments/assets/0241af06-2dac-4fa7-86c5-556a16fd6edb" />



### **✅ Task 2 — Supervised Learning (Test Result Prediction)**

Built a prediction model to estimate **Test Results** using features such as:

* Age
* Gender
* Medical Condition
* Medication
* Hospital
* Billing Amount
* Admission Type
* Insurance Provider, etc.

### **ML Workflow Includes:**

* Data preprocessing
* Label encoding for categorical features
* Train-test split
* Random Forest Regressor
* Performance metrics:

  * MAE
  * MSE
  * R² Score
* Predicted vs Actual graph

🔍 **Files:**

* `Task2_SupervisedLearning_EDA.ipynb`

---

<img width="1580" height="1180" alt="Actual vs Predicted Test Results (Task 2)" src="https://github.com/user-attachments/assets/0f8623df-2d2d-487c-98eb-80463e6bf3df" />


### **✅ Task 3 — Unsupervised Learning (Anomaly Detection)**

Performed anomaly detection on **Billing Amounts** using:

* **Isolation Forest Model**

### **Outputs:**

* Detected unusually high or low billing values
* Marked anomalies with flags
* Plotted anomaly points on scatter chart
* Highlighted potential data-entry errors or extreme medical cases

🔍 **Files:**

* `Task3_AnomalyDetection.ipynb`

---

<img width="1980" height="1180" alt="Room Number Distribution  (Task 3)" src="https://github.com/user-attachments/assets/129d2343-ad38-4119-bb03-66c7912351ca" />


### **✅ Task 4 — AI Doctor Recommendation Generator (LLM-Based)**

An AI-style clinical recommendation generator that uses:

* Age
* Medical Condition
* Medication
* Predicted Test Result

### **Outputs:**

* Doctor-style interpretation
* Personalized medical advice
* Clean paragraph-based recommendation text

🔍 **Files:**

* `Task4_Doctor_Recommendation.ipynb`
* `doctor_recommendation.pdf`

---

## 📁 **Dataset**

Source:
[https://www.kaggle.com/datasets/prasad22/healthcare-dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

### **Dataset Columns**

* Name
* Age
* Gender
* Blood Type
* Medical Condition
* Date of Admission
* Doctor
* Hospital
* Insurance Provider
* Billing Amount
* Room Number
* Admission Type
* Discharge Date
* Medication
* Test Results

---

## 🛠️ **Technologies Used**

### **Languages & Libraries**

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* ReportLab (for PDF generation)

---

## 📊 **Key Results**

### **Supervised Learning**

| Metric | Score |
| ------ | ----- |
| MAE    | ~0.64 |
| MSE    | ~0.60 |
| R²     | ~0.10 |

### **Anomaly Detection**

* Detected approx. **2% billing anomalies**
* Includes high bills (₹50,000+) and negative bills (possible errors)

### **AI Recommendation Output**

A clean medical advice paragraph created using rule-based LLM-style logic.

---

## 🚀 **How to Run the Project**

### 1. Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Open any task notebook

```
jupyter notebook Task1_EDA.ipynb
```

---

## 📌 **Project Highlights**

✔ End-to-end ML workflow
✔ Clean code, modular, professional
✔ Visualizations included
✔ AI-powered medical recommendation
✔ Perfect for showcasing Data Science + ML + AI skills

